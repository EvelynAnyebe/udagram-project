# Udagram

This is a solution for project of the udacity cloud devops engineer course as part of the ALX-T scholarship. In this project we create a infrastructure for the deployemnt of a high availability website. We envision this website to be like `instagram` hence the name `udagram`.

## Creating the Infrasturcture

To create the infrastructure for this project we need to run these scripts.

1. **Network Stack**: ./create.sh udagram udagram-network.yml udagram-parameters.json
   If you make extra changes to the network code, use `./update.sh udagram udagram-network.yml udagram-parameters.json`.

2. **Servers**:
