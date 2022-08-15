## PROJETO COMPASS.UOL- Programa de Bolsas DEVSECOPS

Neste repositório contem todas as etapas das entregas do Projeto:

## 1° Entrega - Atividade em grupo
Entrega final da Sprint: Grupo 6- Atividade prática no desenvolvimento da trilha de Certificação LPI Linux Essentials e Docker.

### 🎯 Metas a serem entregues:
📝 Instruções:

- 1 - Instalar uma imagem ORACLE LINUX na sua última versão; 

- 2 - Ajustar a rede da máquina em IP de classe A com a máscara /24; 

- 3 - Deixar a rede em modo NAT; 

- 4 - Ajusta LVMs para as partições /home, /var e /tmp; 

- 5 - Configura o HOSTNAME; 

- 6 - Ajustar DNS com o nome nodejslabdocker; 

- 7 - Configura a rede do servido com IP fixo; 

- 8 - Configura o SSH; 

- 9 - Bloquear o acesso SSH para o root; 

- 10 - Criar um filesystem /var/lib/docker com 10GB em ext4; 

- 11 - Criar um projetor versionado; 

- 12 - Subir um docker; 

- 13 - instalar uma imagem da aplicação nodejs e suba um wordpress neste nodejs. Via docker; 


📝LINK da primeira atividade com mais detalhes: 

https://github.com/RefesonCompassUol/LabDockerNodeJs



## 2° Entrega - Atividade individual

Entrega final da Sprint: Linux com Redes

## 🎯 Metas a serem entregues:

📝 Instruções:

- 1 - Subir uma segunda VM (seguindo as mesmas regras da atividade anterior);

- 2 - Mudar a VLAN das 2 para BRIGDE e fazer os ajustes necessarios;

- 3 - Criar uma apresentação de slides com 1 slide para cada um dos topicos:

      3.1 - O que faz o comando systemctl docker status?

      3.2 - Onde esta localizado o arquivo de configuração da placa de rede?
 
      3.3 - Qual o comando usado para conectar em outro servidor?
      
      3.4 - O que faz o comando rmdir?

- 4 - Configurar a relação de confiança entre as duas VMs;

- 5 - Fazer o versionamento da atividade;

- 6 -Fazer a documentação explicando o processo de instalação do Linux.

🐧 Documentação da Instalação do Linux [Documentação Instalação Oracle Linux.pdf](https://github.com/RefesonPinho/SecondProjectCompassUol/files/9169147/Documentacao.Instalacao.Oracle.Linux.pdf)

📝Link da Apresentação: [Apresentação Final Sprint.pptx](https://github.com/RefesonPinho/SecondProjectCompassUol/files/9172536/Apresentacao.Final.Sprint.pptx)


## 3° Entrega - Atividade em grupo
Entrega final da Sprint: Trilha: KUBERNETES

## 🎯 Metas a serem entregues:
- 1 - Crie um namespace chamado labwordpress, tudo o que for feito deverá estar dentro deste namespace;

- 2 - Faça o apply do arquivo de service do MySQL mude a porta padrão do banco MySQL para 3308;

- 3 - Crie o arquivo secret que deverá conter o password do banco MySQL, lembre-se de criar uma senha com fortes padrões de segurança;

- 4 - Faça o apply do arquivo de PersistentVolumeClaim do MySQL para um capacity de 3GB;

- 5 - Faça o apply do arquivo de deployment do MySQL, crie também um volume mount no deployment do MySQL chamado “mysql-persistent-storagelab", apontando para /var/lib/mysql. Lembre-se de criar o volume em si com o mesmo nome do volume mount;

- 6 - Faça o apply do arquivo de service do Wordpress altere para a TCP Port 80;

- 7 - Faça o apply do arquivo de PersistentVolumeClaim do Wordpress, para um capacity de 3GB;

- 8 - No arquivo de deployment do Wordpress, crie um volume mount no deployment do Wordpress chamado “wordpresspersistent-storage-lab", apontando para /var/www/html. Lembre-se de criar o volume em si com o mesmo nome do volume mount;

- 9 - No arquivo de deployment do wordpress, insira o secret contendo o password do MySQL, criado no começo do exercício.

- 10 - Faça o apply do arquivo de deployment do wordpress;

- 11 - Verifque se os pods, os services e os pvcs foram criados da forma correta dentro namespace criado no início deste exercício;

- 12 - Verifique qual foi a URI gerada através do ingress do Kubernetes;

- 13 - Copie essa URI do Ingress e cole no browser para abrir a tela inicial do wordpress

- 14 - Criar documentação

📝Link da terceira atividade com mais detalhes:

https://github.com/RefesonPinho/NetworkProjectCompassUol/tree/main/Servidor2/Kubernetes


