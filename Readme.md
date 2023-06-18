→ Versionamento de arquivos

- Branch → Linhas do tempo
- Commit → Postar/Salvar
- Merge → Junção das Branch's
- Remote → GitHub
- Push → Enviar o commit local, para o Remote
- Pull → Puxar os arquivos do GitHub para sua maquina

***Commands***
```java
Ver Status
$ git status

Inicializar repositório
$ git init

Preparar os arquivos para o commit
$ git add _nomedoarquivo_


Commit
$ git commit -m 'mensagem para identificar o commit'

Mudar de Branch
$ git branch -M 'main'
// Neste caso para a branch main(master)

Comando para conectar os arquivos locais com o GitHub, fornecido pelo GitHub
$ git remote add origin https://github.com/LuizManoeldev/ProjetoGit.git
				// Url do repositorio
Enviar os arquivos do repositório local para o repositório do GitHub.
$ git push -u origin main
