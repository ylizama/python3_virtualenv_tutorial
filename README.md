# Python3 Virtualenv Setup for MAC
Steps to set up virtual environments using python3

##### Requirements
* Python 3
* Pip 3

```bash
$ brew install python3
```

Pip3 is installed with Python3

##### Installation
Install virtualenv via pip:
```bash
$ pip3 install virtualenv
```

##### Usage
Create virtualenv:
```bash
$ virtualenv -p python3 <desired-path>
```

Activate the virtualenv:
```bash
$ source <desired-path>/bin/activate
```

Deactivate the virtualenv:
```bash
$ deactivate
```


[More info about Virtualenv](https://virtualenv.pypa.io/en/stable/)
