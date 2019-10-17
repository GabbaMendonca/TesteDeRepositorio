# Trabalho do PIM III

**Instruções para o Tabalho do PIM - GitHub**

Tenha instalado o Git na sua maquina.

> https://git-scm.com/downloads

Faça uma conta no GitHub.

Faça um Fork do projeto na sua conta.

Faça o clone do projeto na sua maquina

> git clone (URL do seu repositorio)

Crie um branch nova. ( Recomendo não trabalhar a master para evitar conflitos )

> git checkout –b (Nome da sua branch)

Trabalhe na alteração. E faça o commit com o camando abaixo.

> git commit -m "comentários das alterações"

Mandando somente a brach nova para o seu repositorio remoto

> git push origin (Nome da sua branch)

Faça um Pull Request da sua branch neste repositorio na branch Developer.

**Atualizar o seu repositorio local e remoto**

Para atualizar o seu repositorio remoto no GITHUB e local com este repositorio central do projeto utilize estes comandos.

Adicione o repositorio central no seu GIT

> git remote add upstream ( Endereço desse repositorio )

    *upstream é o nome do meu repositorio remote na sua maquina, poderia ser qualquer outro nome.
    
    Ex.: git remote add repositorio_central

Faça o download das atualização do repositorio central

> git fetch upstream

Agora faça a "junção" na sua branch master local.

> git rebase upstream/master

Agora "suba" para seu repositorio remoto no GITHUB

> git push origin master

Agora sempre que for atualizar o master local com a master do repositorio central use os comandos :

> git fetch upstream

> git rebase upstream/master


---

Como fazer um Pull Resquest para o GitHub

https://www.youtube.com/watch?v=nT5o3jWrGCM

https://www.youtube.com/watch?v=E8MPe6tCMo8

---

Code Review & Pull Request no Github

https://www.youtube.com/watch?v=MpsNF-EyytQ

---

Como resolver conflitos de Pull Request

https://www.youtube.com/watch?v=PsKJbdGtQYc

---

Trabalhando um projeto em vários repositórios locais - Resolvendo conflitos

https://www.youtube.com/watch?v=yNCBpSX9Yj4

---

GIT - Criando ramificações do projeto (branch e merge)

https://www.youtube.com/watch?v=iRs6sQOPcvg
