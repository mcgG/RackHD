Steps
-----------

# Modification:
      Changed docker-compse.yml in /RackHD/example/infrasim to support 3 nodes.

# Install Docker and Docker-compose
      https://docs.docker.com/install/
      https://docs.docker.com/compose/install/

# Steps:
```shell
      git clone https://github.com/mcgG/RackHD
      cd RackHD/example/rackhd
      sudo docker-compose -f docker-compose.yml up -d #start RackHD dockers
      cd ../infrasim
      sudo docker-compose up -d  #start infrasim dockers
      
      # Get node BMC ip
      sudo docker-compose logs | grep 'Either host IP'
```
