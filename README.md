# metadata(Instance ID & Instance Type)-json

## What it does
- Query the metadata of an ec2 instance within AWS and provide a json formatted output. 
- Retrieve the value of instance ID, instance type, instance state.

## How to install
- [Create an EC2 Linux instance on AWS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
- [SSH into the instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html)
- Install Python 3 and git on your instance 
    - `sudo yum install python3 git`
- Clone this repository
  - `git clone https://github.com/Aparna-Rath/Metadata`
- Install pipenv
  - `sudo pip3 install pipenv`
- Open the repository on your instance
  - `cd aws-metadata-json`
- Install project dependancies
  - `pipenv install`


## How to run
- Open the `src` folder
  - `cd metadata/src`
- Run whichever script you need:
  - `python3 get_data.py`
  


