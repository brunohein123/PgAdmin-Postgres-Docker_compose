# PgAdmin-Postgres-Docker_compose
A docker compose file with PgAdmin and Postgres

## ENGLISH
**1** - Download the file and save it in a folder (the file name must be ***docker-compose***)
</br>**2** - Open the file with your favorite text editor
</br>**3** - Change in the file docker-compose the line ```/ localdatasave``` specifying the path where the data of your database will be written
</br>**4** - Also change the line where ```youremail@email.com``` is written to your PgAdmin login email
</br>**5** - Save the file
</br>**6** - Open a terminal and run the command:```docker-compose up -d```
</br>**7** - Type ```docker stats``` and see if the PgAdmin and Postgres services are running

## PORTUGUÊS
**1** - Baixe o arquivo e o salve em uma pasta (o nome do aquivo deve ser **docker-compose**)
</br>**2** - Abra o aquivo com seu editor de texto favorito
</br>**3** - Mude no arquivo docker-compose a linha ```/localdatasave``` especificando o caminho aonde os dados do seu banco de dados serão gravados
</br>**4** - Mude tambem na linha aonde está escrito ```youremail@email.com``` para o seu email de login no PgAdmin
</br>**5** - Salve o arquivo
</br>**6** - Abra um terminal e execute o comando :```docker-compose up -d```
</br>**7** - Digite ```docker stats``` e veja se o serviço do PgAdmin e do Postgres estão sendo executados
