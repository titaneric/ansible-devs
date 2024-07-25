# Dev-Tools


Run ansible

```
docker run -it -v $(pwd):/ansible willhallonline/ansible:2.16.4-bookworm-slim bash

ansible-galaxy role install -r requirements.yml

ansible-playbook -i inventory.yml -vv -kK playbook.yml
```

