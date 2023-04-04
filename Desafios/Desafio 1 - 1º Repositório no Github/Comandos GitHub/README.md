# Comandos importantes do GitHub

### Gerenciamento de Repositório

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git remote add origin URL` | Adiciona um repositório remoto ao repositório local |
| `git remote -v` | Exibe a lista de repositórios remotos |
| `git push -u origin branch` | Envia as mudanças locais para o repositório remoto e estabelece o upstream da branch |
| `git pull --rebase origin branch` | Atualiza o repositório local com as mudanças do repositório remoto usando o rebase |
| `git push origin --delete branch` | Remove uma branch do repositório remoto |
| `git fetch` | Obtém as atualizações do repositório remoto sem fazer merge com a branch local |
| `git tag -a tag -m "mensagem"` | Cria uma nova tag com a mensagem especificada |


<br><br>


### Issues

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git issue list` | Exibe a lista de issues do repositório |
| `git issue show número` | Exibe detalhes de uma issue especificada |
| `git issue create -t "título" -b "corpo"` | Cria uma nova issue |
| `git issue close número` | Fecha a issue |


<br><br>


### Pull Requests

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git fetch origin pull/ID/head:NOME_BRANCH` | Obtém o pull request de um usuário específico e cria uma nova branch local com as mudanças |
| `git pull origin NOME_BRANCH` | Atualiza a branch local com as mudanças do pull request |
| `git push origin NOME_BRANCH` | Envia as mudanças da branch local para o pull request |
| `git checkout --patch origin/NOME_BRANCH` | Navega pelas mudanças do pull request em um modo interativo |


<br><br>


### Colaboração

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git clone URL` | Clona um repositório remoto para o repositório local |
| `git fork URL` | Cria um fork do repositório remoto para sua conta no GitHub |
| `git pull origin main` | Atualiza a branch local com as mudanças da branch main do repositório remoto |
| `git push origin main` | Envia as mudanças locais da branch main para o repositório remoto |
| `git merge branch` | Realiza o merge da branch especificada com a branch atual |
| `git branch -d branch` | Remove a branch especificada |
| `git stash` | Armazena as mudanças em um stash temporário |
| `git stash apply` | Aplica as mudanças do stash mais recente |
| `git stash list` | Exibe a lista de stashes armazenados |
| `git stash drop` | Remove o stash mais recente |


<br><br>


