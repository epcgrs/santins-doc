# Guia de Criação de Temas Wordpress </>

## 1 - Iniciando

<p>Primeiro passo é fazer o download do arquivo a seguir:</p>
<a href="downloads/start.zip" download>Baixe aqui.</a>

### Windows
No windows você deve ter o Git bash instalado. Então extraia o arquivo wget.exe na pasta 
`C:\Program Files\Git\mingw64\bin\wget.exe`

Após extraia o arquivo `start.sh` na sua pasta de projetos do seu servidor local e execute-o.

### Linux / MacOs
Somente extraia o arquivo `start.sh` na sua pasta de projetos do seu servidor local e execute-o.

## 2 - Instalando

* Ao executar o arquivo `start.sh` digite o nome do projeto, oscript irá baixar o wordpress, plugins e tema padrão utilizados na Santins.
* Crie um banco de dados;
* Edite o arquivo `wp-config.php` na pasta do projeto;
* Crie um vhost para seu projeto;
* Edite o arquivo gulpfile.js na pasta do tema `wp-content\themes\seutema\gulpfile.js` alterando apenas o proxy para seu vhost;

## 3 - Executando
* Execute o comando `npm run start` na pasta do tema;