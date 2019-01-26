# ansible-fluentd
install td-agent and plugin and so on kernel parameter settings

# td-agent setup ansible script

set up td-agent

## Provides

* td-agent
* td-agent-plugins
* kernel & limits settings(http://docs.fluentd.org/articles/before-install)

## Requires

1. Ansible
2. Any Linux OS

## Usage

### change hosts file 

	[server]  
	192.168.1.20  

### Run the Playbook

`$ ansible-playbook -i hosts site.yml`

