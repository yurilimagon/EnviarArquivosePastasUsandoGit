# EnviarArquivosePastasUsandoGit
Tutorial de como enviar aquivos e pastas via comandos git

O intuito do tutorial é auxiliar o envio de pastas e arquivos via terminal git.

      
      
      COMO ENVIAR ARQUIVOS PARA UM REPOSITÓRIO PUBLICO GITHUB POR GIT

//  Tutorial de como instalar o git em varios sistemas:
//  https://www.hostinger.com.br/tutoriais/tutorial-do-git-basics-introducao/

//  Criado por: Yuri Lima Gonçalves

//Configuração do Git Localmente
//Seu nome completo que vai ser utilizado em qualquer commit.
git config --global.user "Seu Nome e Sobrenome"

//Seu endereço de email que vai ser utilizado em qualquer commit.
git config --global.email "seu@email"



//Acesse um diretório local onde você quer alocar seu repositório clonado (Documentos por exemplo)
//Abra o terminal e digite o comando abaixo para acessar o diretório criado para alocar seu
//repositório
0)cd Nome_do_Diretório

//Crie um repositório no site do github ou utilize um já criado.

//Clonar o repositório github desejado para o sei diretório local.
//Em seguida se seu repositório for private seu usuário e senha github serão solicitados.
1)  git clone github.com/usuario/Nome_do_repositorio

//Adicione uma pasta ou arquivo que deseja adicionar no seu repositório.
2)  git add Nome_da_pasta ou Nome_do_arquivo

//Adicione um commit (confirmação) nos arquivos que serão enviados.
3)  git commit -m "Inicialização do MeuProjeto"

//Utilizar o comando git push para enviar os arquivos.
4) git push

//Em seguida se seu repositório for private seu usuário e senha github serão solicitados.
