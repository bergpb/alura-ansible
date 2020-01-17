##### Anotações do curso

Hello world com ansible:
`ansible wordpress -u vagrant --private-key .vagrant/machines/wordpress/virtualbox/private_key -i hosts -m shell -a 'echo Hello, World'`
Obs: Necessário repassar a private key para não repassar a senha pela linha de comando. É uma boa prática criar chaves ssh para autenticação do servidor com o cliente.

Rodando comando com provisioning.yml criado:
`ansible-playbook provisioning.yml -u vagrant -i hosts --private-key .vagrant/machines/wordpress/virtualbox/private_key`

