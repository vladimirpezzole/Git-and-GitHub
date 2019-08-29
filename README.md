# Git-and-GitHub
Links e resumos sobre Git e GitHub

Principais comandos:
* `git init` // inicia a linha do tempo
* `git add` // adiciona ou atualiza mudanças para irem para a linha do tempoo
* `git commit` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo / commit
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // gerenciar novas linhas do tempo
* `git checkout` // manipula as linhas do tempo
* `git merge` // unir linhas do tempo
* `git push` // envia alterações locais para o repositório remoto
* `git clone` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto
* `git pull --rebase origin master` // Use rebase com Cuidado, git pull --rebase é pra ser usado quando se deseja atualizar (pull) um ramo local com um ramo remoto que, antes de ser enviado para a rede (push), sofreu mesclagem por rebase. O  git rebase é uma espécie de merge também, mas usa uma lógica diferente. Ao invés de gerar um novo commit, ele reaplica cada um dos commits da branch local "em cima" (no topo) do último commit da branch remota. 