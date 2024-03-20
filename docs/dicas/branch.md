Para criar uma nova branch no GitHub usando a linha de comando, você pode seguir estes passos básicos usando o Git:

1. **Clone o Repositório** (se ainda não tiver clonado): Se você ainda não tem o repositório em sua máquina local, você pode cloná-lo usando o comando `git clone <URL_do_repositório>`.

2. **Navegue até o Diretório do Repositório**: Use o comando `cd` para navegar até o diretório do repositório clonado.

3. **Crie a Nova Branch**: Use o comando `git checkout -b <nome_da_branch>` para criar uma nova branch e mudar para ela ao mesmo tempo. Substitua `<nome_da_branch>` pelo nome que você deseja dar à sua nova branch.

4. **Envie a Nova Branch para o GitHub**: Após fazer as alterações que deseja na nova branch, você pode enviá-la para o GitHub usando o comando `git push origin <nome_da_branch>`. Isso fará com que a nova branch e suas alterações sejam enviadas para o repositório remoto no GitHub.

Então, para resumir, o processo seria algo assim:

```bash
# Clone o repositório (caso ainda não tenha clonado)
git clone <URL_do_repositório>

# Navegue até o diretório do repositório
cd <diretório_do_repositório>

# Crie e mude para a nova branch
git checkout -b <nome_da_branch>

# Faça as alterações necessárias e adicione, comite...

# Envie a nova branch para o GitHub
git push origin <nome_da_branch>
