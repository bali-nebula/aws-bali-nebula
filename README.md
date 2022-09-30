## The Bali Nebula™
<img src="https://craterdog.com/images/CraterDogLogo.png" width="50%">

### _\* \* \* NOTICE \* \* \*_
_This project is still under development and is for reference purposes only. If
you are interested in this project or have suggestions on how to improve it feel
free to contact us at [craterdog@gmail.com](mailto:craterdog@gmail.com)._

### Quick Links
For more information on this project click on the following links:
 * [project vision](https://github.com/craterdog-bali/aws-bali-nebula/wiki/Vision)
 * [project overview](https://github.com/craterdog-bali/aws-bali-nebula/wiki)
 * [bali document notation](https://github.com/craterdog-bali/go-bali-document-notation/wiki)
 * [digital notary](https://github.com/craterdog-bali/go-bali-digital-notary/wiki)
 * [nebula services](https://github.com/craterdog-bali/go-bali-nebula-services/wiki)

### Getting Started
Prior to cloning this project, several local tools need to be installed.

#### Installing HomeBrew
We use [homebrew](https://brew.sh/) to install the other things we need, so here is how to install it:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update
brew doctor
```

#### Installing Python3
The scripts that are used in this repository depend on [python3](https://www.python.org/). Here is how to install it:
```
brew install python
python --version
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
pip install boto3
```

### Contributing
Project contributors are always welcome. Create a
[fork](https://github.com/craterdog-bali/aws-bali-nebula) of the project and add cool
new things to the Bali Nebula™. When you are ready to contribute the changes create a subsequent
["pull request"](https://help.github.com/articles/about-pull-requests/). Any questions and
comments can be sent to [craterdog@gmail.com](mailto:craterdog@gmail.com).

