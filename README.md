## Data Pipelines with Python (video edition)

Welcome to the code repository for [Data Pipelines with Python]()! If you have any questions reach out to @kjam on Twitter or GitHub.

### Code Structure

Most of the code covered in the videos is here; but not all of it. I highly recommend you take time to type out all the code along with the videos and simply use these scripts to "double check" or remind yourself of the work you've already completed.

### Installation

If you are using Python2, use the requirements.txt file. If you are using Python3, use the py3_requirements.txt file. 

```pip install -r requirements.txt```

or 

```pip install -r py3_requirements.txt```

### Yahoo Finance API

There is a [good writeup in German for the Finance API](http://brusdeylins.info/tips_and_tricks/yahoo-finance-api/) which I used as a starting point to download newer-time data.

### Python2 v. Python3

This repository is primarily compliant for both versions. Please let me know if you run into any bugs!


### Ansible Playbook

To use as a template rather than as a direct template, I've included a working playbook in the deploy folder. If you try and run it directly, you will likely receive some errors. Please read through the notebook and take a look at the directives and determine which you need and which you don't. It also requires a .ssh/authorized_hosts file as well as a config file located in `celeryapp/config/prod.cfg`. If you run into other errors, I highly recommend reading through [the Ansible
documentation](http://docs.ansible.com/ansible/) or searching on StackOverflow.

### Corrections?

If you find any issues in these code examples, feel free to submit an Issue or Pull Request. I appreciate your input!

### Questions?

Reach out to @kjam on Twitter or GitHub. @kjam is also often on freenode. :)
