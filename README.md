# devops_ac02  
Nome: Francisco Luiz Soares Camini RA: 1902975  

#print01.PNG:  
Pagina do GITHUB onde no canto superior esquerdo da imagem ao clicar em NEW logo a frente de REPOSITORIES cria-se o Repositorio;

#prin02.PNG:  
Ao clicar em NEW vide explicação do Print01.png acima Nesta Pagina o usuario do github é direcionado para uma pagina para informar os parametros do repositorio: 
De cima para baixo onde: 
OWNER é o proprietario, Caso tenha mais de uma conta ou empresa vinculada podera selecionar entre elas;
REPOSITORY NAME é onde é informado o nome do repositorio;
TIPO DE REPOSITORIO: podera ser escolhido entre PUBLIC (PUBLICO) ou PRIVATE(PRIVADO) e isto determinara se o repositorio eh de acesso publico ou não;
INITIALIZE THIS REPOSITORY WITH: são arquivos adicionais ao repositorio a ser criado
Após selecionar as configurações acima devera clicar em CREATE REPOSITORY

#print03.PNG:  
Este print eh Representado pela imagem onde se tem uma visao incial ja dentro do repositorio e no canto superior esquero apresenta o nome do repositorio criado seguido do nome do usuario do github.


#print04.PNG:  
Ainda dentro do repositorio criado no print02.png ao clicar em CODE na aba HTTPS pode se obter a URL que ira permitir criar o clone no GIT BASH copiando a url com a extenção .git e colando logo a frente do comando git clone "url" (proximos prints para detalhes);


#print05.PNG:  
Print representa a tela do git bash onde no comando CD "NOME DA UNIDADE \ NOME DA PASTA" EXEMPLO CD c:\impacta\ para se ter acesso a pasta onde sera armazenado o clone do repositorio criado nos passos anteriores;

#print06.PNG:  
ainda na pasta de exemplo: c:\impacta\ ao usar o comando GIT LOG o mesmo mosta erro fatal pois como nao foi clonado o repositorio por nesta pasta nao possuir o arquivo .git apresenta a erro fatal;

#print07.PNG:  
neste print foi executado o comando GIT CLONE "URL DO REPOSITORIO" para clonar o repositorio criado nos passos anteriores e disponibilizando no computador local, exemplo do comando usado para clonar git clone https://github.com/LuizCamini/devops_ac02.git

#print08.PNG:  
usado git status fora da pasta para demonstrar erro mesmo apos clonado o repositorio porem não havia ainda acessado a pasta do repositorio recem clonada

#print09.PNG:  
apos utiliza o comando CD devops_ac02 foi acessada a pasta contendo o repositorio recem clonado e utilizando o comando git status eh apresentado informacoes sobre a branch master e que nao existe commits pendentes

#print10.PNG:  
utilizando o git log se obtem informacoes detalhadas sobre como esta o estado do repositorio neste ponto so temos informacoes do commit inicial feito na criacao do repositorio no fit hub e informacoes sobre autor e dados de acesso;

#print11.PNG:  
Executado o comando git status apos adicionar os 10 primeiros arquivos de prints mostra os arquivos disponiveis em LOCAL Working Directory representados pela cor vermelha;

#print12.PNG:  
Apos executar o comando "git add ." os arquivos foram para a staging (o ponto representa que todos os arquivos serao adicionados na staging) area ainda em ambiente local aguardando o commit representados pela cor verde;

#print13.PNG:  
executado o comando git commit -m "nome do commit" exemplo utilizado para este primeiro commit git commit prints_01_a_10 onde os arquivos foram disponibilizados em local repo ainda local;

#print14.PNG:  
Executado o comando git push onde os arquivos commitados foram disponibilizados no repositorio remoto;

#print15.PNG:  
executado o comando git log onde agora apresenta os dois commits executados o initial commit efetuado na criacao do repositorio atraves da pagina do git hub e o commit efetuado pelo git bash;

#print16.PNG:  
representa os arquivos no repositorio remoto apos o commit no git bash;

#print17.PNG:  
executado o comando git fech para trazer todos os repositorios remotos para o repositorio local;

#print18.PNG:  
executado o comando git status apos o git fech onde eh mostrado o status dos arquivos no repositorio local que possui modificacao;
executado o git log para mostrar detalhes sobre commits executados e dados de usuario;

#print19.png:  
executado o comando git merge onde o mesmo apresentou que os arquivos estao prontos;
executado o comando checkout e o mesmo mostrou o arquivo readme.md




