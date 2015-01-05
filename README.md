# What is this
This is a repo showing example fig files on how to run popular web apps using docker and fig -- the proper way where one container does one thing.

# Contributing 
## Format
Each directory in this repo is an app.  If there are multiple versions of an app then there should be multiple versions within the directory.  Within each directory there should be a fig.yml and a README.md.

### README.md
Within the README.md file please include all environment vars and volumes used to help others use the fig.yml file.

### fig.yml
Do not use the build attribute.
Use the image attribute.
Use only publicaly available images. 
