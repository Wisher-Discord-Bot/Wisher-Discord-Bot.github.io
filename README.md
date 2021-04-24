<a href="https://wisher-discord-bot.github.io/"><p align="center"><img width="400px" src="https://cdn.discordapp.com/attachments/796511540777582632/834079721905192960/20ffee02-798d-44b4-8fed-d1fcc6ef5c21.png"></a>

# _Manual de início rápido_

## Primeiro de tudo, instale o Git:
Git: https://git-scm.com/downloads

O instalador do Git irá instalar:
 - Git
 - Chocolatey
 - Python 3

Você também vai precisar de:
 - um editor de texto de sua escolha.
recomendação: "Visual Studio Code" ou "Atom"

(todos esses (exceto o editor de texto) são instalados juntos do git pelo próprio instalador, só não desmarcar a caixinha q fala pra instalar tudo junto)

---

## Para começar a editar o site, digite no prompt:
```bat
cd %LOCAL-DE-DOWNLOAD% EX.: %userprofile%/documents/GitHub/Wisher-Discord-Bot.github.io

git clone https://github.com/Wisher-Discord-Bot/Wisher-Discord-Bot.github.io.git
```

---

## Para dar upload das modificaçoes:
```bat
cd %LOCAL-DO-REPOSITORIO%

git add .

git commit -m "MENSAGEM DE COMMIT AQUI"

git push
```
**NÃO ESQUEÇA DE SALVAR** os arquivos que vão ser enviados pro github **ANTES** de dar esses comandos

---

## Para atualizar os arquivos locais com as modificaçoes mais recentes feitas pelos outros programadores digite:
```bat
cd %LOCAL-DO-REPOSITORIO%

git pull
```
#### esta etapa é necessaria para dar upload das modificaçoes armazenadas localmente. caso alguma mudança entre em conflito, o Git abrirá o editor de texto padrao mostrando onde estao as divergencias

---

## Caso dê acesso negado, ou o programa pediu pra criar um fork, cancele a criaçao do fork e digite no prompt:
```bat
git config --global user.name ACCOUNT-NAME-HERE

git config --global user.email ACCOUNT-EMAIL-HERE
```
Depois disso, se foi a primeira vez, ele pedirá pra autenticar no navegador, daí terá que logar com a sua conta pelo navegador e voila
