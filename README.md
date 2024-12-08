# workshop-docker

Normalmente fariamos essa configuracao para o ambiente python

```bash
pyenv local 3.12.5
pip install pipx
pipx install poetry
poetry init
poetry env use 3.12.5
```

Com o Docker podemos instalar isso com um comando
* atraves do Dockerfile podemos incluir o comando

```bash
FROM python:3.12.5
```
