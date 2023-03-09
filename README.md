# UdacityAlx-DevOps-project2
This project is an assessment for the Udacity ALX-T Cloud DevOps Engineer Nanodegree Program to Deploy a high-availability web app using CloudFormation

# SETUP
1. Create Network Infrastructure
```bash
./create.sh STACK_NETWORK_NAME hmax-network.yml hmax-network-params.json
```

2. Create Servers
```bash
./create.sh STACK_NAME hmax-servers.yml hmax-servers-params.json
```


# UPDATE
To update any of the stack, use the update.sh script e.g
```bash
./update.sh STACK_NAME STACK.yml STACK-PARAMS.json
```

## Load Balancer Endpoint
```bash
http://Serve-WebSe-4X66ZIGCTNJV-1851735937.us-west-2.elb.amazonaws.com
```