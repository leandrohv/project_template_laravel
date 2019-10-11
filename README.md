# Aplicação Laravel Modelo
* 1° Criar o projeto no phpdocker.io
* 2° Descompactar os arquivos dockers na pasta do projeto
* 3° Subir os containers
    * command: "docker-compose up -d"
* 4° Conectar no container php-fpm 
    * command: "docker exec -it CONTAINER_NAME /bin/bash"
* 5° Instalar laravel
    * command: "composer create-project --prefer-dist laravel/laravel src versao do laravel"
    ######Obs.: Após a instalação sair do container.
* 6° Setar dono da pasta da aplicação
    * command: chown -R $USER:$USER FOLDER_APLICATION
* 7° Setar permissão na pasta da aplicação
    * command: chmod -R 777 FOLDER_APLICATION
* 8° Alterar os volumes dos containers e incluir ./src
* 9° Alterar o timezone no arquivo config/app.php, para 'timezone' => 'America\Sao_Paulo',
* 10° Alterar o locale no arquivo config/app.php, para obter o melhor idioma para a internacionalização ,


    Ambiente com Laravel usando Docker
    https://www.youtube.com/watch?v=cmuS6tg__so

