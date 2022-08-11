# C**ompass.uol sprint 6**

# **Bolsistas** <br>

[Kaiana Miguel De Medeiros](https://github.com/kaianamiguel); <br>
[Lucas Freiberger de Souza](https://github.com/lucasfrei); <br>
[Refeson Dos Santos Pinho](https://github.com/RefesonPinho)

## Objetivo

Desenvolver, com o apoio dos instrutores e scrums master, as habilidades com a tecnologia de kubernetes. E assim melhor a relação entre colegas e aprimorar a capacidade de lidar e solucionar os problemas.

Ao final, fazer um deploy do wordpress vinculando ao banco de dados mysql através do kubernet

## **Requisitos**

[RNF-01] Crie um namespace chamado labwordpress, tudo o que for feito deverá estar dentro deste namespace;

[RNF-02] Faça o apply do arquivo de service do MySQL mude a porta padrão do banco MySQL para 3308;

[RNF-03] Crie o arquivo secret que deverá conter o password do banco MySQL, lembre-se de criar uma senha com fortes padrões de segurança;

[RNF-04] Faça o apply do arquivo de PersistentVolumeClaim do MySQL para um capacity de 3GB;

[RNF-05] Faça o apply do arquivo de deployment do MySQL, crie também um volume mount no deployment do MySQL chamado “mysql-persistent-storagelab", apontando para /var/lib/mysql. Lembre-se de criar o volume em si com o mesmo nome do volume mount;

[RNF-06] Faça o apply do arquivo de service do Wordpress altere para a TCP Port 80;

[RNF-07] Faça o apply do arquivo de PersistentVolumeClaim do Wordpress, para um capacity de 3GB;

[RNF-08] No arquivo de deployment do Wordpress, crie um volume mount no deployment do Wordpress chamado “wordpresspersistent-storage-lab", apontando para /var/www/html. Lembre-se de criar o volume em si com o mesmo nome do volume mount;

[RNF-09] No arquivo de deployment do wordpress, insira o secret contendo o password do MySQL, criado no começo do exercício.

[RNF-10] Faça o apply do arquivo de deployment do wordpress;

[RNF-11] Verifque se os pods, os services e os pvcs foram criados da forma correta dentro namespace criado no início deste exercício;

[RNF-12] Verifique qual foi a URI gerada através do ingress do Kubernetes;

[RNF-13] Copie essa URI do Ingress e cole no browser para abrir a tela inicial do wordpress

[RNF-14] Criar documentação

---

[RNF-15] Poderá ser feito na VM instalando o Minikube, ou via
Docker for Windows

---

# **Entrega**

- A entrega será durante o horário da primeira daily (quinta-feira, 11 de agosto de 2022, 14:30 gtm3)
- Com o link do versionamento e documentação

# **Ferramentas**

- GIT.
- GITHUB
- VIRTUALBOX
- DOCKER
- MINIKUBE
