# Learn-GIT

git

Getting Started with git. Download and install git in your local machine from below link.

Download Git : https://git-scm.com/downloads

optionally you can download Git CLI. 

Download(git CLI) : https://cli.github.com/

### Error Message :
_'git' is not recognized as an internal or external command,_

Make sure you install git in your local machine



Download Link (gitCLI) : https://cli.github.com/

git [-v | --version]

git -v    OR   git --version      command is used to check version installed in your machine.  (use cmd tool )


### Error Message :
_fatal: unable to access 'https://github.com/ladpriteshkumar/Portfolio.git/': SSL certificate problem: unable to get local issuer certificate_

[Reference](https://stackoverflow.com/questions/23885449/unable-to-resolve-unable-to-get-local-issuer-certificate-using-git-on-windows)

Open Git Bash and run the command if you want to completely disable SSL verification.

git config --global http.sslVerify false

Note: This solution opens you to attacks like man-in-the-middle attacks. Therefore turn on verification again as soon as possible:

git config --global http.sslVerify true
