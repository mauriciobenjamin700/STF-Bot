## Comandos Básicos do Git

### Add

O comando `git add` é usado para adicionar arquivos ao índice (staging area) do Git para que eles sejam incluídos no próximo commit.

```bash
git add <nome_do_arquivo>      # Adiciona um arquivo específico ao índice
git add .                      # Adiciona todos os arquivos modificados ao índice
```
### Commit
O comando git commit é usado para confirmar as alterações feitas e criar um novo commit com essas alterações.

```bash
git commit -m "Mensagem do commit"     # Cria um novo commit com uma mensagem
```

### Push
O comando git push é usado para enviar os commits locais para um repositório remoto.
```bash
git push <remote_name> <branch_name>    # Envia os commits locais para o repositório remoto
```

### Pull
O comando git pull é usado para atualizar o repositório local com as alterações do repositório remoto. Ele combina git fetch e git merge.

```bash
git pull <remote_name> <branch_name>    # Atualiza o repositório local com as alterações do remoto
```

### Merge
O comando git merge é usado para combinar os commits de uma branch com outra branch.

```bash
git checkout <branch_destino>           # Muda para a branch onde você quer mergear as alterações
git merge <branch_origem>               # Combina os commits da branch_origem com a branch_destino
```

Lembre-se de substituir <remote_name>, <branch_name>, <nome_do_arquivo>, <branch_origem> e <branch_destino> pelos nomes corretos de acordo com o seu contexto.

Esses são alguns dos comandos básicos do Git que você usará com frequência durante o desenvolvimento de projetos.