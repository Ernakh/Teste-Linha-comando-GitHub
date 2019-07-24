# Teste-Linha-comando-GitHub
Projeto de teste


1º - Criar uma conta no GitHub
2º - Criar um repositório
	-Nome e descrição
	-publico ou privado?
3º - Branch
	- uma forma de se trabalhar com diferentes versões de um mesmo projeto
	- Por padrão, existe o branch Master
4º - Criar um Commit
	- Commit é uma forma de salvar as mudanças
	- Cada commit tem sua mensagem: Explicar o que foi alterado e o pq!
	- é uma foram de histórico para os demais programadores
5º - Pull Request
	- Quando você tem alguns commits e deseja mesclar o que você fez com o que existe no 	    repositorio, ou seja, "esta tudo pronto e posso enviar ao servidor", você faz um 		    Pull.Que sobe os seus commits para o repositório.
	- O pull pode passar por analise de um administrador



Passo 1 - Instalar o Git

Passo 2 - Configurar
$ git config --global user.name "YOUR NAME"
$ git config --global user.email "YOUR EMAIL ADDRESS"

Passo 3 - Clonar
Com o repositorio criado, devemos clona-lo.
git clone https://github.com/<username>/site.git

Passo 4 - Criar arquivos, alterar arquivos, excluir arquivos

Passo 5 - Usar o Add

Passo 6 - Gerar commit

Passo 7 - Fazer um push



Comandos básicos:
git add <arquivos...>
Este comando adiciona o(s) arquivo(s) em um lugar que chamamos de INDEX, que funciona como uma área do git no qual os arquivos possam ser enviados ao Github. É importante saber que ADD não está adicionando um arquivo novo ao repositório, mas sim dizendo que o arquivo (sendo novo ou não) está sendo preparado para entrar na próxima revisão do repositório.

git commit -m "comentário qualquer" 
Este comando realiza o que chamamos de “commit”, que significa pegar todos os arquivos que estão naquele lugar INDEX que o comando add adicionou e criar uma revisão com um número e um comentário, que será vista por todos.

git push Push (empurrar) 
é usado para publicar todos os seus commits para o github. Neste momento, será pedido a sua senha.

git status 
Exibe o status do seu repositório atual


