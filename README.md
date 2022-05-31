# payment-service-rvw
Component behorende bij Ticket Booking Camunda demo opstelling

## Code gedeployed middels GitHub Actions

## Aanmaken instanties EC2 Linux 2
* toevoegen security rechten om poort 15672 open te zetten

## Installation Amazon EC2 Linux 2
* sudo yum update
* sudo curl -sL https://rpm.nodesource.com/setup_14.x | sudo bash -
* sudo yum install -y nodejs
* sudo npm install -g typescript
* sudo npm install -g ts-node



* sudo yum install -y amazon-linux-extras
* sudo amazon-linux-extras enable java-openjdk11
* sudo yum clean metadata
* sudo yum install java-11-openjdk
* sudo update-alternatives --config javac --> selecteer optie java11
* sudo yum install maven
* 

## Run NodeJs Fake Services

If you want to understand the code, please have a look into this get started tutorial: https://github.com/camunda/camunda-platform-get-started/tree/main/nodejs

```
cd fake-services-nodejs
npm update
ts-node src/app.ts
```
