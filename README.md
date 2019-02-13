# Hyperledger-Fabric - Invoice

### Development Environment
+ Operating System: Ubuntu 18.04 LTS – 64 bit
+ Go version: go1.11.5 linux/amd64

### Pre-Requisites:
+ Docker Engine: Version 17.03 or higher
+ Docker-Compose: Version 1.8 or higher
+ Node: 8.9 or higher (note version 9 and higher is not supported)
+ npm: v5.x
+ git: 2.9.x or higher
+ Python: 2.7.x
+ A code editor of your choice, we recommend VSCode

### Installation Of Go:
+ Go to this link https://golang.org/doc/install, then click the Download the archive
+ Go to the terminal then type the following:

   tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz <br />
   export PATH=$PATH:/usr/local/go/bin

+ To check the version of go, type the following in the terminal:

    go version

### Installation Of Postman or Insomnia:
#### Postman
+ Go to this link https://www.getpostman.com/downloads/ 
+ Select the applicable platform for your OS type
+ Then click Download and Install the application
#### Insomnia
+ Go to this link https://insomnia.rest/download/
+ Select the applicable platform for your OS type
+ Then click Download and Install the application

### Setting up a Network:
+ Clone the projects with the following links: <br />
https://github.com/bchinc/blockchain-training-labs <br />
https://github.com/hyperledger/fabric-samples 
   
+ To clone the links given above, enter the following to the terminal: <br />
git clone https://github.com/bchinc/blockchain-training-labs <br />
git clone https://github.com/hyperledger/fabric-samples 

#### Go to the terminal and type the following to make a new folder inside the fabric-samples:
cd fabric-samples <br />
mkdir invoice

#### In the Files, go to folder blockchain-training-labs and copy the following files:
<pre>blockchain-training-labs/
       | ---- node/
              | ---- app.js
              | ---- enrollAdmin.js
              | ---- package.json
              | ---- registerUser.js
              | ---- startFabric.sh
</pre>
