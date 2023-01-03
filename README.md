# docker-compose
Cómo instalar docker-compose | How to install docker-compose (.yml) (.yaml)

Docker compose en Ubuntu (Linux)
Creamos carpeta cli-plugin dentreo de .docker/

mkdir -p ~/.docker/cli-plugins/

Después descargamos docker Compose desde la Repo Github oficial. Tened en cuenta la versión y arquitectura de vuestro servidor. En este caso es para Ubuntu (Linux).

curl -SL https://github.com/docker/compose/releases/download/v2.14.2/docker-compose-linux-x86_64 -o ~/.docker/cli-plugins/docker-compose

Ahora ya podemos usar docker-compose.
