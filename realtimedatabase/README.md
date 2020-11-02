# PythonFireBaseDataBase
`Neste repositório estudo sobre a implementação do serviço RealtimeDataBase do Firebase em um servidor python.`

# Acessando o Realtime Database
`Dado que o projeto firebase já foi criado.`
* Primeiramente vá em Realtime Database, acesse o serviço, e clique em Criar Banco de Dados;
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img1.png?raw=true)

* Selecionar o __modo de teste__;
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img2.png?raw=true)

* Então você será levado ao console do serviço, que deve se parecer com a imagem:
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img3.png?raw=true)

* Vá em configurações do projeto, para obter as credenciais;
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img4.png?raw=true)

* Obtenha as credenciais(estas são as minhas, não da empresa);
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img5.png?raw=true)

* As credenciais devem ser definidas dentro da variável de ambiente .env, que deve ser criada no diretório do projeto.

* No caso de banco de dados nosql, os registros são inseridos como jsons, não mais como querys.
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img6.png?raw=true)

![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img7.png?raw=true)

# Configuração Necessária no Banco de Dados
* É necessário definir os índices dos valores, por tanto faça como a imagem.
# Como rodar
![alt text](https://github.com/Beevi-Cognitive/PythonFirebase/blob/master/realtimedatabase/imagens/img8.png?raw=true)


* Copie o código abaixo para instalação da lib necessária no notebook:
    `import sys`
    `!{sys.executable} -m pip install python-dotenv pyrebase`

 - No mesmo diretório onde está sendo executado o notebook, deve conter o arquivo .env configurado de acordo como mencionado na página inicial deste repositório
