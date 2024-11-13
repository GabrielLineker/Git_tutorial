# Git_tutorial

## Todas as operações podem ser feitas a partir do terminal do vscode.

git init
- inicia um novo projeto git na pasta

git add <nome-arquivo> / . (O . chama todos)
- add os arq q estão prontos pra serem commitados

git commit -m "Mensagem commit"
- commita os arq no histórico

git log
- mostra os últimos commits, e alterações

git status
- mostra o status dos commits

git diff
- mostra oq foi alterado
- e o q tem de alteração

git merge
- junta as branchs

git branch
- mostra a branch atual

git branch -b <nome-da-branch>
- cria uma nova branch, a partir da branch atual

git checkout <nome-branch>
- muda para a branch nomeada

git remote add <nome> <url>
- add um repositório no git hub (linka com a nuvem) (nome=origin)

git push <nome> <nome-da-branch>
- manda o arquivo para o repositório no git hub

git pull <nome> <nome-da-branch>
- pega os arquivos do repositório e tras para a maquina

git fetch
- atualiza o arquivo de acordo com as alterações realizadas no repositório
- sincroniza os dados

