### Setup

- make sure the host machine can ssh into the destination machine
- put all the vm ips in hosts file
- create .env and .config.js from the using example format from frontend and backend in the root.

Then:

```
- ansible-playbook -i hosts setup.yml
or
- ansible-playbook -i hosts setup.yml --connection=local  // for localhost
```
