Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui;

https://github.com/steniovm/my_first_steps
também criei o https://github.com/steniovm/teste

Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. 
Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

mkdir my_first_steps
cd my_first_steps
git init
git remote add origin git@github.com:steniovm/my_first_steps.git
git add .
git commit -m "veremos"
git push git@github.com:steniovm/teste  (não sei como eu buguei o repositório my_first_steps, daqui pra frente usei o repositório teste)

Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. 
Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

git add ola_mundo.txt
git commit -m "ola mundo"
git push git@github.com:steniovm/teste

Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. 
Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa.

# arquivo ignorado
serei_ignorado.txt

