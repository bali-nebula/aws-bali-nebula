## The Bali Nebula™ (v2)
<img src="https://craterdog.com/images/CraterDogLogo.png" width="50%">

_**WARNING**_
_This project is still in its early stages and the cloud architecture is likely to change._

### Quick Links
For more information on this project click on the following links:
 * [project overview](https://github.com/craterdog-bali/aws-bali-nebula/wiki)
 * [component framework](https://github.com/craterdog-bali/js-bali-component-framework/wiki)
 * [digital notary](https://github.com/craterdog-bali/js-bali-digital-notary/wiki)
 * [document repository](https://github.com/craterdog-bali/js-bali-document-repository/wiki)
 * [type compiler](https://github.com/craterdog-bali/js-bali-type-compiler/wiki)
 * [virtual machine](https://github.com/craterdog-bali/js-bali-virtual-machine/wiki)
 * [nebula API](https://github.com/craterdog-bali/js-bali-nebula-api/wiki)
 * [nebula services](https://github.com/craterdog-bali/js-bali-nebula-services/wiki)

### Getting Started

### Installing HomeBrew
We use [homebrew](https://brew.sh/) to install the other things we need, so here is how to install it:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
```

#### Installing Python3
The scripts that are used in this repository depend on [python3](https://www.python.org/). Here is how to install it:
```
brew install python3
python3 --version
```

#### Installing AWS CLI
The [AWS CLI](https://docs.aws.amazon.com/cli/latest/reference/index.html#cli-aws) is used by some of the bash scripts in this repository. Here is how to install it:
```
brew install awscli
aws --version
```

#### Installing Boto3
Some of the [AWS S3 CLI](https://docs.aws.amazon.com/cli/latest/reference/s3/index.html) commands don't work well, so instead we use the [python3 boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) library. Here is how to install it:
```
curl https://bootstrap.pypa.io/get-pip.py | python3
pip3 install boto3 --user
```

### Contributing
Project contributors are always welcome. Create a
[fork](https://github.com/craterdog-bali/aws-bali-nebula) of the project and add cool
new things to the Bali Nebula™. When you are ready to contribute the changes create a subsequent
["pull request"](https://help.github.com/articles/about-pull-requests/). Any questions and
comments can be sent to [craterdog@gmail.com](mailto:craterdog@gmail.com).

