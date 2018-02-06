Steps
-----------

# Modification:
      Changed docker-compse.yml in /RackHD/example/infrasim to support 3 nodes.

# Steps:
```shell
      git clone https://github.com/mcgG/RackHD
      cd RackHD/example/rackhd
      sudo docker-compose -f docker-compose.yml up -d #start RackHD dockers
      cd ../infrasim
      sudo docker-compose up -d  #start infrasim dockers
```
