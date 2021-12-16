# Desafio de Projeto sobre Git/Github da DIO
Repositório criado para o Desafio de Projeto.

## Links Úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)

git init - Inicia o projeto com um controle de vers�o - nesse caso no git
git clone - Clonar um repositorio ou um projeto remoto
git add . -> Chama todos arquivos criados para o git ou git add index.html vai chamar s� o arquivo index.html
git status -> Mostra como est� o arquivo, mostra se foram alterados e ainda n�o foram enviados pro git...
git commit -m "Meu primeiro commit" -> Salva as altera��es feitas no diret�rio local
git branch -> mostra todas as branchs
git log -> Mostra as altera��es que foram feitas, por quem, qual horario..
- criar um reposit�rio no github e copiar o link
git remote add origin https://github.com/RafaelRamosMachado/projeto_curso_git.git -> adiciona o caminho do github no reposit�rio local
git push -u origin master -> Envia do reposit�rio local para o repositorio remoto
- abrir o projeto e fazer uma altera��o no arquivo index.html
git status -> Mostra como est� a situa��o dos arquivos, se j� foram modificados..
git add index.html -> Adiciona o arquivo index.html
git status -> Mostra como est� a situa��o dos arquivos, se j� foram modificados..
git commit -m "Adicionando estrutura html inicial" -> Salva as altera��es feitas no diret�rio local
git log -> Mostra as altera��es que foram feitas, por quem, qual horario..
git push -> publica as altera��es no github, nesse caso foi s� git push pois j� tinha sido informado git push -u origin master
git branch -> Mostra todas as branchs e em qual ela est�
git checkout <<nome branch>> -> Troca de branch
git branch -D <<nome_da_branch>> -> Deleta a branch
git branch <<nome branch>> -> Cria uma branch nova
git checkout -b <<nome_da_nova_branch>> -> Cria uma branch nova e j� altera pra ela
- criar um arquivo contato.html
git status -> vai mostrar que foi criado um arquivo contato.html mas n�o foi adicionado ao git
git add contato.html -> adiciona o arquivo contato.html ao git
git status
git commit -m "Criando arquivo html de contato" -> Salva as altera��es feitas no diret�rio local
git status
git log
git push origin contato -> Envia do reposit�rio local para o repositorio remoto
git merge contato -> mescla, Atualiza as branchs e iguala elas, nesse caso adicionou a branch master na contato e adicionou a branch contato na master 
git push -> publica as altera��es no github

