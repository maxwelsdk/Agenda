# Agenda
exercicio_alura
Comandos básicos GIT

// Lista usuários
git config --list

// Define o usuário

git config --global user.email sam@google.com

git config --global user.name username

git init

// Este comando é usado para criar um novo repositório GIT. Uso:

git add

// Adicionar arquivo ou pasta

git add temp.txt

// O comando git add pode ser usado para adicionar arquivos ao índice. Por exemplo, o seguinte comando irá adicionar
um arquivo chamado temp.txt presente no diretório local para o índice:

git clone

//O comando git clone é usado para fins de verificação de repositório. Se o repositório estiver em um servidor remoto, use:

git clone https://github.com/maxwelsdk/Agenda.git

git commit

//O comando git commit é usado para confirmar as alterações na cabeça. Tenha em atenção que quaisquer alterações efetuadas não irão para o repositório remoto. Uso:

git commit –m “coloque sua mensagem aqui”

git status

//O comando git status exibe a lista de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados. Uso:

git remote

//O comando git remote permite que um usuário se conecte a um repositório remoto. O comando a seguir lista os repositórios remotos atualmente configurados:
git remote -v

// Para adicionar um repositório
git remote add origin https://github.com/maxwelsdk/Agenda.git

git push

// Envia as alterações feitas para o ramo mestre do repositório remoto associado ao diretório de trabalho
-u  usuário logado. (quando não for o mesmo, não utilizar o comando -u)
origin nome dados no comando git remote para o repositório remoto.

git push -u origin master
