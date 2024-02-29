# Projeto: Castrastro de Usuários - NodeJS/Express
### 1 - O que é?
Um aprimoramento do repositório <a href="https://github.com/JhoneRodrigues/user-registration" target="_blank">User-registration</a>. Executando três aplicações web para cadastro de usuários em Node.js.

### 2 - Objetivo
Este projeto tem como principal objetivo criar um ambiente otimizado para utilização em containers com o Docker Compose, incluindo o equilíbrio de cargas com o Nginx. Apresento esta versão aprimorada do projeto <a href="https://github.com/JhoneRodrigues/user-registration" target="_blank">User-registration</a> para destacar as melhorias proporcionadas pelo Docker Compose no processo de criação de ambientes para desenvolvimento, teste ou produção.

### 3 - Como executar
Para cumprir o objetivo e executar esse projeto:

#### I - Tecnologias necessárias
- Git para clonagem do repositório;
- Docker Compose para execução dos contêineres.

#### II - Comandos para executar a aplicação
- Faça a clonagem deste projeto
```git
git clone https://github.com/JhoneRodrigues/user-registration2
```  
- Em sua máquina, dentro do repositório "./user-registration", basta executar o comando abaixo para subir todo o ambiente.
```docker
docker compose up
```
#### III - Seu ambiente de produção está pronto :white_check_mark:
- Acesse http://localhost:81 para entrar na aplicação e testar o cadastro de usúario;
- Acesse http://localhost:8081 para entrar no Docker-express e vizualizar os dados.
<p> OBS.: Se atualizar a página da aplicação web verá no Prompt o Nginx te direcionando automaticamente para diferentes instancias(node1, node2 ou node3), demonstrando na prática o balanceamento de carga.</p>

#### Parar a aplicação e excluir os contêineres
- Use o atalho CRTL + C para parar a aplicação;
- Execute o comando abaixo para exluir os contêineres e as imagens criadas.
```docker
docker compose down
```

## <b> Vamos nos conectar..!</b><img src="https://github.com/0xAbdulKhalid/0xAbdulKhalid/raw/main/assets/mdImages/handshake.gif" width ="80">
<a href="https://www.linkedin.com/in/jhonerodrigues/" target="_blank">
<img src="https://img.shields.io/badge/linkedin:  jhone rodrigues-%2300acee.svg?color=405DE6&style=for-the-badge&logo=linkedin&logoColor=white" alt=linkedin style="margin-bottom: 5px;"/>
</a>
