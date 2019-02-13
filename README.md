# Hyperledger-Fabric - Invoice

### DEVELOPMENT ENVIRONMENT:
    + Operating System: Ubuntu 18.04 LTS – 64 bit
    + Processor: Intel® Core™ i3-5010U CPU @ 2.10GHz × 4
    + RAM: 12GB
    + Go version: go1.11.5 linux/amd64
    + Device Type: ASUS Laptop X455LJ

PRE-REQUISITES:
    • Docker Engine: Version 17.03 or higher
    • Docker-Compose: Version 1.8 or higher
    • Node: 8.9 or higher (note version 9 and higher is not supported)
    • npm: v5.x
    • git: 2.9.x or higher
    • Python: 2.7.x
    • A code editor of your choice, we recommend VSCode

--> Use the following commands to download and install the prerequisites:

curl -O https://hyperledger.github.io/composer/latest/prereqs-ubuntu.sh
chmod u+x prereqs-ubuntu.sh
./prereqs-ubuntu.sh

INSTALLATION OF GO:
    • Go to this link https://golang.org/doc/install,  then click the Download the archive
    • Go to the terminal then type the following:
      
      tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz
      export PATH=$PATH:/usr/local/go/bin
      
    • To check the version of go, type the following in the terminal:
          
          go version

INSTALLATION OF POSTMAN:
    • Go to this link https://www.getpostman.com/downloads/ 
    • Select the applicable platform for your OS type
    • Then click Download and install the application

SETTING UP A NETWORK:
    • Clone the projects with the following links:
        ◦ https://www.github.com/benedictsuarez888/blockchain-training-labs
        ◦ https://github.com/hyperledger/fabric-samples 
          
--> To clone the links given above, enter the following to the terminal:
	
git clone https://www.github.com/benedictsuarez888/blockchain-training-labs
git clone https://github.com/hyperledger/fabric-samples 


    • Go to the terminal and type the following to make a new folder inside the fabric-samples:

          cd fabric-samples
          mkdir fabinvoice
    • In the Files, go to folder blockchain-
