Steps to setup on aws

- update yum and install git first : sudo yum update -y, sudo yum install -y git
- clone this repo
- clone https://github.com/Abhivision/rRobo
- Go to aws directory
      - Run : bash install.sh
      - run : sudo rebbot and again make aws ssh connection
      - run everything from setup.sh being into aws directory
            (this will setup the database with price and news)
- Go to rRobo directory 
  - install everything from install.R
  - run first initial.sh and then run.sh this will run r codes
  (Command to run R file : Rscript filename)
