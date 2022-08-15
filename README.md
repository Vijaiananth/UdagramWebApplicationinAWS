### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


In YAML code, the `${EnvironmentName}` would be substituted with `Udagram` accordingly.


**Files:**

1. Udagram-network-parameters.json - contains parameters for creating AWS network.
2. Udagram-network-parameters.yml - This yml cloud formation scripts utlizes the parameters file and creates the network.
3. Udagram-server-parameters.json - contains parameters for creating Web application servers and configurations.
4. Udagram-server-parameters.yml - This yml cloud formation scripts utlizes the parameters file and creates the servers.

**Scripts:**

Below script creates stack which deploys network in AWS.

./create.sh Udagram-network Udagram-network.yml Udagram-network-parameters.json

Below script creates stack which deploys servers in AWS.

./create.sh Udagram-servers Udagram-servers.yml Udagram-server-parameters.json