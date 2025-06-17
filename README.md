# VictoryCenter-DevOps


To run this playbook for installing Github Actions Self-Hosted Runner use:

ansible-playbook install_gh_actions_runner.yml --extra-vars "runner_user=user1 github_account=account1 github_repo=myorg1”

or in JSON format:

ansible-playbook install_gh_actions_runner.yml --extra-vars "{"github_account": "account1", "github_repo": "myorg1", "runner_user": "user1"}”


Docs:
https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_variables.html#json-string-format