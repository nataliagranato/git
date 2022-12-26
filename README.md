# Repositório de aprendizado sobre Git.
Repositório utilizado para aprender os primeiros passos e comandos básicos do git.

# Comandos

As configurações do Git são armazenadas no arquivo .gitconfig localizado dentro do diretório do usuário do Sistema Operacional (Ex.: linux /home/nataliagranato).

Nome de exibição
```
git config --global user.name "Leonardo Comelli"
```

Email do meu repositório
```
git config --global user.email leonardo@software-ltda.com.br
```

Criando um novo repositório localmente
```
git init
```

Verificando o estado dos arquivos e diretórios do meu repositório local
```
git status
```

Adicionando um arquivo específico
```
git add arquivo1
```

Adicionando um diretório específico
```
git add estudo-git
```

Adicionando todos os arquivos e diretórios
git add .
```
ou

git add --all
```

Adicionando um arquivo para ser ignorado
```
git add -f app18.log
```

Realizando commit de um arquivo
```
git commit arquivo2
```

Realizando commit de vários arquivos
```
git commit arquivo1 arquivo2 arquivo3
```

Realizando commit com uma mensagem de informação
```
git commit -M "Atualizando o repositório"
```

Adicionando um repositório remoto ao repo local
```
git remote add origin git@github.com:nataliagranato/git.git
```

Exibindo os repositórios remotos
```
git remote -v
```

Removendo arquivos ou diretórios
```
git rm arquivo1
git rm -r estudo-git
```

Exibindo o histórico do repositório
```
git log
```

Enviando arquivos para o repo remoto
```
git push origin:main
```

Atualizando o repositório local
```
git pull
```

Criando uma nova branch
```
git branch student
```

Trocando de branch
```
git checkout student
```

Voltando para a branch principal
```
git checkout main
```

Apagando uma branch
```
git branch -d student
```

