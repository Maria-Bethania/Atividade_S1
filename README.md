# Atividade Semanal - S1

        Conexão de Repositório Local ao GitHub

## Descrição:

        O objetivo é conectar um repositório local ao GitHub;
        Permite o versionamento e compartilhamento de projetos.

# Passo a passo

* Abrir uma pasta de atividade específica para o exercício;
* Abrir o Git Bash nesta mesma pasta;

        O Git Bash permite você usar os comandos Git no Windows.

* No Git Bash, dois comandos iniciais:

        1. git init: Transforma a pasta em um repositório git, e permite o versionamento do código;
        2. code . : Abre o VsCode na pasta atual, para que se possa trabalhar no projeto;

* No VSCode, na pasta Atividade_S1, criar um arquivo “README.md”.
* No arquivo "README.md", detalhar o exercício;
* No github do navegador, criar um novo repositório;

        Acessar o site do GitHub [aqui](gitub.com), fazer login ou criar uma conta, e criar um novo repositório.

* Novamente, no terminal do VS Code, colocar o comando: git add . 

        Adiciona todas as alterações na pasta do projeto, preparando-as para o commit.  

* Fazer o primeiro commit, no terminal do VSCode, com o comando: git commit – m “Initial commit”;

        Captura as mudanças realizadas.

* No terminal do VSCode, coloque o comando: git branch -M main;

        Renomeia o branch principal para "main".

* Ainda no terminal do VSCode, entre com: git remote add origin [URL desejada](https://github.com/Maria-Bethania/Atividade_S1.git);

*Por fim, no terminal do VSCode, escreva: $ git push -u origin main;

## Observação

* Estes são os comandos que você deve usar sempre que fizer alterações no repositório:

        git add .: Adiciona todas as mudanças na pasta atual.
        git commit -m "nome do commit": Cria um novo commit.
        git push origin main: Envia os commits para o repositório remoto no branch "main".

## Conclusão

        Ao seguir este passo a passo, é possível conectar o repositório local ao GitHub;
        Permite o versionamento e compartilhamento dos projetos de forma mais eficaz.


