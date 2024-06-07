# medgodevelop

Comandos pré-deploy heroku

-- Adicionando buildpack de nodejs
heroku buildpacks:set heroku/nodejs -a nome do app no heroku

-- Conferindo buildback foi instalado
heroku buildpacks -a medgo-test-web-app
