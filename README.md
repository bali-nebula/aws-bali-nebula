![Logo](https://raw.githubusercontent.com/craterdog-bali/bali-project-documentation/master/images/CraterDogLogo.png)

### Bali Nebula Modules
This project provides the AWS CloudFormation templates needed to manage the [_Bali Nebula™_](https://github.com/craterdog-bali/bali-project-documentation/wiki). The Bali Nebula™ consists of the following layered modules:

![Pyramid](https://raw.githubusercontent.com/craterdog-bali/bali-project-documentation/master/images/BaliPyramid.png)

_**WARNING**_
_This project is still in its early stages and the cloud architecture is likely to change._

### Bali Nebula Architecture
The modules are used to create an Amazon AWS based cloud architecture:

![Architecture](https://raw.githubusercontent.com/craterdog-bali/bali-project-documentation/master/images/The%20Bali%20Nebula%20Architecture.png)

### Installing HomeBrew and Python3
The scripts that are used in this repository depend on [python3](https://www.python.org/). Here is how to install it using [homebrew](https://brew.sh/):
```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
brew install python3
python3 --version
```

### Installing Boto3
Some of the [AWS S3 CLI](https://docs.aws.amazon.com/cli/latest/reference/s3/index.html) commands don't work well, so instead we use the [python3 boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) library. Here is how to install it:
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
pip install boto3 --user
```

### Installing AWS CLI
The [AWS CLI](https://docs.aws.amazon.com/cli/latest/reference/index.html#cli-aws) is used by some of the bash scripts in this repository. Here is how to install it:
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
pip install awscli --upgrade --user
aws --version
```
