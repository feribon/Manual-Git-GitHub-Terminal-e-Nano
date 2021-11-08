# Meu manual de Git, GitHub e Terminal!

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

* 