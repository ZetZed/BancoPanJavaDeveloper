# Comandos importantes do Git

### Configuração do Git

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git config --global user.name "Seu nome"` | Define o nome do usuário para commits |
| `git config --global user.email "Seu email"` | Define o email do usuário para commits |
| `git config --global core.editor "Seu editor"` | Define o editor de texto padrão |


<br><br>


### Gerenciamento de Repositório

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git init` | Inicia um novo repositório local |
| `git clone URL` | Clona um repositório remoto para a máquina local |
| `git status` | Verifica o status dos arquivos do repositório |
| `git add arquivo` | Adiciona um arquivo ao staging area |
| `git add .` | Adiciona todos os arquivos modificados e novos ao staging area |
| `git commit -m "mensagem"` | Registra as mudanças no repositório com uma mensagem descritiva |
| `git push origin branch` | Envia as mudanças locais para o repositório remoto |
| `git pull origin branch` | Atualiza o repositório local com as mudanças do repositório remoto |
| `git merge branch` | Combina as mudanças de uma branch com outra |
| `git branch nome` | Cria uma nova branch com o nome especificado |
| `git checkout branch` | Altera a branch atual para a especificada |
| `git log` | Exibe um registro das mudanças no repositório |


<br><br>


### Desfazendo Alterações

| Comando         | Descrição     |   
| --------------------------- | --------------------- | 
| `git reset arquivo` | Remove um arquivo do staging area |
| `git reset` | Remove todos os arquivos do staging area |
| `git revert hash` | Desfaz um commit especificado |
| `git checkout -- arquivo` | Descarta as mudanças não commitadas em um arquivo |
| `git clean -f` | Remove todos os arquivos não rastreados |

