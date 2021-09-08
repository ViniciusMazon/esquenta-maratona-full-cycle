# Sobre
Repo criado com o intuito de registrar o que foi aprendido na aula [Iniciando com Docker e Portainer: Trabalhe com containers do zero](https://www.youtube.com/watch?v=fJk3w3-BHiE&list=WL&index=3) do esquenta da maratona full cycle.

# Como utilizar
Para rodar o projeto
```bash
$ docker-compose up
```

# Anotações
É possivel acessar conteúdo de um container:
```bash
$ docker exec -it <container id> /bin/sh
$ cd app
$ cat index.js
# o conteúdo do arquivo index.js é exibido
```
