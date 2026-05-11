Comando para criar o projeto em um repositorio já existente:

  *docker run -v "./:/app" -p 80:8080 -w "/app" composer/composer php yii serve 0.0.0.0*
