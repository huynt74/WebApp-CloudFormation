# CD12352 - Infrastructure as Code Project Solution
# HUYNT42
- cd starter
## Spin up instructions
./run.sh create us-east-1 high-webapp network.yml network-parameters.json
./run.sh create us-east-1 high-webapp-servers udagram.yml udagram-parameters.json
## Tear down instructions
./run.sh delete us-east-1 high-webapp
./run.sh delete us-east-1 high-webapp-serversp

## Other considerations
./run.sh update us-east-1 high-webapp-servers udagram.yml udagram-parameters.json

## URL
- http://high-w-webap-2cjgttax1ahz-166900204.us-east-1.elb.amazonaws.com/
