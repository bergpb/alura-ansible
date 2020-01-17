##### Anotações do curso

Hello world com ansible
`ansible wordpress -u vagrant --private-key .vagrant/machines/wordpress/virtualbox/private_key -i hosts -m shell -a 'echo Hello, World'`
Obs: Necessário repassar a private key para não repassar a senha pela linha de comando.  

Com o argumento `-vvvv` é possível ver a saída do código mais verboso.