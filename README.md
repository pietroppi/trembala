DOCUMENTO DE ACOMPANHAMENTO – VERSIONAMENTO DE CÓDIGO COM GIT E GITHUB 

Integrantes 

Integrante 1: Pietro Phelipe 

Integrante 2: Daniel de Albuquerque 

Ferramentas Utilizadas 

Git Bash 

Visual Studio Code (VS Code) 

GitHub 

 

1. Todos os Comandos Utilizados 

Inicialização do Projeto 

git init 
git add . 
git commit -m "Projeto inicial" 
 

Conexão com o GitHub 

git remote add origin URL_DO_REPOSITORIO 
git branch -M main 
git push -u origin main 
 

Clonagem do Projeto 

git clone URL_DO_REPOSITORIO 
 

Criação das Branches 

Integrante 1: 

git checkout -b dan 
 

Integrante 2: 

git checkout -b pietro 
 

Envio das Alterações 

Página Home: 

git add . 
git commit -m "Criação página Home" 
git push origin dan 
 

Página Login: 

git add . 
git commit -m "Criação página Login" 
git push origin pietro 
 

Atualização do Projeto 

git checkout master 
git pull origin master 
 

 

2. Prints das Etapas Realizadas 

Inserir os prints das seguintes etapas: 

Emerson, não tirei os prints pois já tinha iniciado o projeto, não sabia que precisava fotografar o que eu estava fazendo. 

3. Explicação do que Foi Feito em Cada Etapa 

Etapa 1 – Criação do Projeto 

Foi criada uma pasta para o projeto e aberta no VS Code. Em seguida, o Git foi inicializado utilizando o Git Bash. 

Etapa 2 – Criação do Repositório 

Foi criado um repositório no GitHub para armazenar o projeto online. Depois, o repositório local foi conectado ao remoto. 

Etapa 3 – Clonagem do Projeto 

Daniel criado para poder trabalhar no mesmo projeto. 

Etapa 4 – Criação das Branches 

Cada integrante criou sua própria branch para desenvolver sua parte sem alterar diretamente a branch principal. 

Etapa 5 – Desenvolvimento 

Daniel desenvolveu a página Home (home.html). 

Pietro  desenvolveu a página Login (login.html). 

Etapa 6 – Merge das Branches 

Após finalizar as tarefas, foram criados Pull Requests no GitHub para juntar as alterações das branches na branch principal (master). 

Etapa 7 – Atualização 

Depois do merge, o projeto foi atualizado para que todos tivessem a versão mais recente. 

 

4. Dificuldades Encontradas 

Tivemos dificuldade em alguns comandos do Git. 

Erramos duas vezes durante o processo de configuração e envio dos arquivos. 

Houve dúvidas na utilização das branches e no envio para o GitHub. 

Em alguns momentos foi necessário repetir comandos devido a erros de digitação. 

 

5. Soluções Adotadas 

Conferimos os comandos antes de executá-los novamente. 

Corrigimos os erros de digitação encontrados. 

Revisamos o passo a passo da atividade. 

Utilizamos o GitHub e o histórico do Git Bash para identificar os problemas. 

Após as correções, conseguimos concluir todas as etapas com sucesso. 

 

Conclusão 

A atividade permitiu aprender na prática como utilizar Git e GitHub para controle de versão. Foram realizados commits, criação de branches, push, pull request e merge, demonstrando o trabalho colaborativo em equipe utilizando ferramentas amplamente utilizadas no mercado de desenvolvimento de software. 
