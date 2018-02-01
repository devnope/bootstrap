Bootstrapper with ansible
---

+ basic install including desktop
+ basic install for server will follow... eventually

_debian based_

**What does it do:**
  + installs all packages named in roles/global-software/tasks/main.yml
  + install xfce and xfce-whisker-plugin ( roles/desktop/tasks/main.yml ) - poorly tested

**HowTo**
	'ansible-playbook playbooks/bootstrap.yml'
