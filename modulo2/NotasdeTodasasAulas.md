## Notas dos comandos aprendidos no módulo 2

1-	Criando um repositório local

mkdir curso-git-e-github   = mkdir é para criar o repositório

ls = é para ver os repositórios que você tem

cd curso-git-e-github = muda para o diretório escolhido

code . = abre o VScode

git init = para inicializar o git na nova pasta criada

git status =fala o status do que você fez, o que não foi comitado ainda, etc.

git remote -v =para falar se ele tem alguma origem remota

git remote add origin URL =para adicionar o repositório a qual ele se vincula

git clone insira-aqui-o-link-do-que-vai-se-clonado           (Lembrar de fazer isso para vincular o repositório do github com meu pc)

git add <file>= para adicionar coisas (e aparecer no git status)

git add . = adiciona todos os arquivos que estão na fila para serem comitados.
Caso você delete um arquivo, tem que colocar o “git add .” de novo para ele “salvar” que aquele arquivo não é para ser comitado. Ou caso você tenha renomeado também.
Markdown: Quando for escrever, colocar “hashtag” na frente. A quantidade de “hashtag” vai dizer o tamanho da letra.

git commit -m “insira aqui descrição da alteração”]

git push = envia as alterações para o github

git pull =pega as alterações do repositório do github e envia para a máquina. Importante quando está trabalhando em equipe.
