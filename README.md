# OpenSSH

## Requirements

* Rancher Secrets

## Setup

### Port mapping

Set your public port to eg. 222.

### Add user

* Add your Private-Key in **Infrastructure**, **Secrets**.
* Upgrade the SSH-Container and add your Private-Key under the Tab **Secrets**.
* Set the name of the secret as $username + ".pub".

## Environment Variables

None.
