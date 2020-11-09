# Prerequisites

* Python3 or Python2.7.9+
* Python Pip3 / Pip

# Install awscli

```bash
pip install --user awscli
export PATH=$PATH:/home/$(whoami)/.local/bin
```

_--user_ is used to install the awscli under your home directory, not to interfere with any existing libraries/installations

create file _~/.aws/credentials_

```bash
[default]
aws_access_key_id=###
aws_secret_access_key=###
region=us-east-1
output=json
```


## TEST

```bash
aws --version
```
