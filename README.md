# Meu manual de Git, GitHub, Terminal e Nano!

## Terminal

* `mkdir` nomeDaPasta
cria uma nova pasta

* `cd` nomeDaPasta
entra na pasta

* `cd` ..
volta uma pasta anterior

* `cd` ../..
volta duas pastas anteriores

* `ls`
mostra os arquivos que tem dentro da pasta

* `echo` 'mensagem'
escreve no terminal

* `echo` 'mensagem' `>>` arquivo.txt
escreve mensagem dentro do arquivo

* `cat` arquivo.txt
abre o arquivo dentro do terminal

* `pwd`
mostra a ramificação das pastas

* `touch` arquivo.txt
cria um arquivo e também atualiza o arquivo

* `less` arquivo.txt
exibe o conteudo do arquivo no terminal

* `cp` arquivo.txt arquivo2.txt
faz uma copia do primeiro arquivo para o segundo que voce nomear

* `mv` arquivo2.txt arquivo3.txt
move o primeiro arquivo para o segundo, se o segundo não existir, ele mesmo cria

* `rm` arquivo.txt
remove o arquivo

* `rm -rf` nomeDaPasta
remove a pasta 

* `clear` 
limpa o terminal

* `history`
mostra uma lista com os comandos que voce usou (`!numero` voce retoma o comando referenciado pelo numero)

* `history | grep` palavra
ele filtra no history tudo o que contenha 'palavra'

* `exit`
fecha o terminal

## Git

* `git config --global user.name` "Felipe Grassi Ribon"
configura seu nome de usuario no git (aparece em todo commit que voce fizer)

* `git config --global user.email` "felipe.gribon@hotmail.com"
configura seu email de usuario no git (aparece em todo commit que voce fizer)

* `git config --global core.editor` "nano"
configura o editor para abrir pelo terminal (util no `git commit --amend`)

* `git config --list`
lista as configurações do seu git

* `git init`
inicializa o repositorio local

* `git add` arquivo.txt
adiciona o arquivo na area temporaria

* `git add .`
adiciona todos os arquivos na area temporaria

* `git commit -m` "breve descrição"
salva os arquivos com o nome acima

* `git status`
mostra como seu arquivo esta (se foi adicionado na area temporaria ou se foi comitado)

* `git log`
mostra o historico dos commits

* `git log --pretty=oneline`
mostra o historico dos commits com codigo e descrição apenas

* `git log --pretty=oneline` -1
menos 1 mostra o ultimo, menos 2 penultimo ...

* `git log --stat`
mostra quantas mudanças que tiveram nos commits

* `git diff`
mostra as mudanças da area temporaria

* `git diff` arquivo.txt
mostras as mudanças somente deste arquivo

* `git diff --name-only`
mostra uma lista com os arquivos que tem diferenças

* `git commit --amend`
edita o commit que voce esta, se voce nao add o arquivo, voce consegue alterar somente a mensagem

* `git reset HEAD` arquivo.txt
tira o arquivo do temporario

* `git checkout --` arquivo.txt
remove a alteração feita no arquivo (tipo um ctrl+z)

* `git branch`
lista as branches

* `git branch` nomeDaBranch
cria uma branch

* `git checkout` nomeDaBranch
muda de branch

* `git branch -D` nomeDaBranch
deleta a branch

* `git checkout -b` nomeDaBranch
cria e ja muda para a branch

* `git merge` nomeDaBranch
voce incorpora a branch acima na sua atual

* `git clone` https://github.com/facebook/create-react-app.git
clona um projeto do GitHub/gitlab/bitbucket para sua maquina

* `git remote add origin` https://github.com/feribon/Manual-Git-GitHub-Terminal-e-Nano.git
linka seu projeto local com o GitHub

* `git push origin` nomeDaBranch
subir seu projeto local para o GitHub (nomeDaBranch la dentro do GitHub)

## Nano

* CTRL+X
Sai do editor.

* CTRL+O
Salva o arquivo.

* CTRL+R
Ler um arquivo em seu arquivo de trabalho atual.

* CTRL+C
Mostra a posição atual do cursor.

* CTRL+K
recorta o texto.

* CTRL+U
cola o texto.

* CTRL+S
Salva o arquivo e continua trabalhando.

* CTRL+T
verifica a ortografia do seu texto.

* CTRL+W
faz uma busca no texto.

* CTRL+A
leva o cursor para o início da linha.

* CTRL+E
leva o cursor para o fim da linha.

* CTRL+G
mostra a ajuda do Nano.

* CTRL+/
e depois insira o n° da linha que deseja ir.

## GitHub

* Criar repositorio
* * escolher nome
* * descrição
* * publico ou privado
* * incluir README.md ou nao



