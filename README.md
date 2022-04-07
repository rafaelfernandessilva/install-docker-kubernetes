# install-docker-kubernetes
Só pra me ajudar nos estudos kubernetes e config do ambiente.

#
Basta colocar os hosts no arquivos hosts.yaml e executar o ansible =)
[all] =  todos os hosts

[main] = k8s master

[node] = workers

#
ansible-playbook playbook.yml -u ubuntu --private-key [sua_chave] -i hosts.yaml
