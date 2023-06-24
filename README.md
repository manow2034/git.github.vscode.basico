# git.github.vscode.basico

	Instalando e integrando git/ githube com vscode:

1.	Abra o prompt de comando e digite git , se não reconhecer significa que não esta instalado na sua maquina.

2.	Acesse : https://git-scm.com/downloads para baixar o git na sua maquina.

3.	Após instalado entre no explorador de arquivos, com botão direito do mouse e clique em git bash here  Este é o comando do git.

4.	Para ver a versão do git digite git –version.

5.	Configure seu usuário no git digitando os seguintes comandos: 

git config –global user.name “Anderson C Mauricio” 

git config –global user.email andersoncorreia2034@gmail.com  use seu email do githube

6.	Agora confira se deu certo as configurações usando o comando git config –list.

7.	Configure seu Windows para ver arquivos ocultos va em:  iniciar > opções do explorador de arquivos > modo de exibição 

desmarcar: “ocultar as extensões dos tipos de arquivos conhecidos”
 marcar: “mostrar arquivos pastas e unidades ocultas.”

8.	Cadastre uma chave SSH para o githube (protocolo para acesso, controla quais computadores podem acessar sua conta em seu nome)
digite no google:  githube ssh > adicionar uma nova chave > Windows > copie o código e cole no getbash e execute.

Acesse o githube > settings >  ssh and gpg > nomeie a maquina que irá acessar > copie sua chave publica acessando a pasta .ssh que está dentro da pasta usuário do computador e cole em key. 

9.	Salvando a  versão de um projeto com git : crie uma pasta no computador para um novo projeto >  abra o vs code > open folder > procure a pasta que você criou > new file > crie um código básico html e salve > vá até a pasta do projeto no computador e teste o arquivo no navegador > dentro da pasta com o botão direito do mouse abra o git bash > digite o comando git init para iniciar o repositório > digite o comando git add . para colocar os arquivos em stage ou seja em uma área temporária > digite o comando git comit –m “mensagem explicativa” para salvar a modificação ou criação de um arquivo > digite o comando git status para acompanhar o progresso, neste caso irá aparecer que não existe arquivos para salvar, se tiver arquivos em stage irá aparecer também. > digite o comando git branch –m main  pois o githube usa o main para salvar projetos por padrão. 

10.	Para enviar seu projeto para o githube: abra sua conta no githube > new repositório > nomeie seu projeto > selecione a opção ssh > copie a linha do comando git remote add origin git@github.com:manow2034/git.github.vscode.basico.git > cole no git bash e execute para fazer a associação do git para o githube.  > use o comando git push –u origin main para finalmente enviar o arquivo para seu repositório no githube.

11. Após fazer alguma modificação no projeto salve a nova versão seguindo os seguintes passos: no git bash execute os comandos: git add . > git commit –m “” >  git push.
