# PythonFireBase
`Neste projeto eu estudo o uso direto e simples do sistema de gerenciamento de usuários do FireBase.`

# Acessando o FireBase
* Primeiramente vá em https://console.firebase.google.com (com a sua conta de gmail previamente logada) -> Adicionar projeto e siga as três etapas simples de criação de um projeto;
![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase1.png?raw=true)


* Dentro do seu projeto, acesse o item Authentication:
    - Na aba Users é retornada as informações de cadastro dos usuários;
![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase2.png?raw=true)

- Na aba Sign-in method é informado os tipos de cadastramento aceitos pelo Firebase(por email, pelo gmail, pelo facebook, pelo github,..., e até pelo smartphone, acredito que desta forma conseguimos implementar o sistema de segurança de dois passos);
![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase3.png?raw=true)

- Na aba Templates é definido informações sobre o email que será enviado ao usuário cadastrado em algum dos três eventos:
    - Verificação do endereço de email (no momento do cadastro);
    - Redefinição de senha;
    - Alteração do endereço de email.
![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase4.png?raw=true)


- Na aba Usage é retornada informações referentes ao uso do serviço em relação ao período de faturamento.
![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase5.png?raw=true)

# Como rodar
- Abra o notebook e execute o primeiro bloco de comandos para a instalação do pyrebase e suas dependências, libs necessárias para a comunicação com o Firebase;

- No segunco bloco de código será feita a instalação da lib dotenv, o que vai nos permitir esconder do github informações de credenciais da aplicação. Estas informações são acessadas em Firebase SDK snippet, ao final da página Configurações, acessada como segue a figura:
 ![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase6.png?raw=true)

 - No mesmo diretório onde está sendo executado o notebook, crie um arquivo chamado .env, onde será colocada as credenciais obtidas do passo anterior. O conteúdo do arquivo deve ser da seguinte forma:

apiKey="oconteudodeapikeyaqui"
authDomain="oconteudodeauthaqui"
databaseURL="oconteudodedatabaseaqui"
projectId="oconteudodeprojectidaqui"
storageBucket="oconteudodestoragebucketaqui"
messagingSenderId="oconteudomessagingaqui"
appId="oconteudodeappidaqui"
measurementId="oconteudodemeasurementidaqui"

chave="valor" (obtido de var firebaseConfig)

# Rodar os comandos
- Os blocos seguintes executam o cadastramento, o login e o reset do password. Executá-los e conferir o email recebido em seguida.

