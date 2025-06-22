
docker login -u krishnahogale
docker build -t krishnahogale/simpletimeserver .
docker tag krishnahogale/simpletimeserver krishnahogale/simpletimeserver:latest
docker push krishnahogale/simpletimeserver
docker run -p 80:5000 krishnahogale/simpletimeserver
docker run -p 5000:5000 krishnahogale/simpletimeserver






 git clone https://github.com/kri-sh27/particle41.git
    2  ls
    3  cd particle41/
    4  python3 --version
    5  python3 -m venev myenv
    6  sudo apt install python3-venv
    7  $ sudo apt-get update
    8  sudo apt-get update
    9  pip --version
   10  pip3 --version
   11  apt install python3-pip
   12  python3 -m venev myenv
   13  sudo apt install python3-venv
   14  python3 -m venev myenv
   15  python3 -m venv myenv
   16  ls
   17  source myenv/bin/activate
   18  ls
   19  pip install -r requirement.txt 
   20  python3 app.py 
   21  # Add Docker's official GPG key:
   22  sudo apt-get update
   23  sudo apt-get install ca-certificates curl
   24  sudo install -m 0755 -d /etc/apt/keyrings
   25  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
   26  sudo chmod a+r /etc/apt/keyrings/docker.asc
   27  # Add the repository to Apt sources:
   28  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
   29  sudo apt-get update
   30  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   31  sudo docker run hello-world
   32  docker ps 
   33  docke ps -a
   34  docker ps -a
   35  vi Dockerfile
   36  ls
   37  docker login -u krishnahogale
   38  docker build -t krishnahogale/simpletimeserver .
   39  ls
   40  mv requirement.txt requirements.txt
   41  docker build -t krishnahogale/simpletimeserver .
   42  ls
   43  docker tag simpletimeservice krishnathogale/simpletimeservice:latest
   44  docker tag simpletimeserver krishnathogale/simpletimeserver:latest
   45  docker tag simpletimeserver krishnahogale/simpletimeserver:latest
   46  docker images
   47  docker tag krishnahogale/simpletimeserver krishnahogale/simpletimeserver:latest
   48  docker images
   49  docker push krishnahogale/simpletimeserver
   50  docker run -p 8080:5000 krishnahogale/simpletimeserver
   51* 
   52  docker run -p 5000:5000 krishnahogale/simpletimeserver
   53  docker run -p 5000:8080 krishnahogale/simpletimeserver
   54  docker run krishnahogale/simpletimeserver
   55  docker run -p 5000:5000 krishnahogale/simpletimeserver
   56  docker run -p 8080:8080 krishnahogale/simpletimeserver
   57  docker run -p 5000:8080 krishnahogale/simpletimeserver
   58  docker run -p 80:5000 krishnahogale/simpletimeserver
   59  ls
   60  vi Dockerfile 
   61  history