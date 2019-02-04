web: JEKYLL_ENV=staging jekyll serve --no-watch --port $PORT --host 0.0.0.0 --config _config.staging.yml
web:    java $JAVA_OPTS -jar webapp/target/dependency/jetty-runner.jar --port $PORT webapp/target/*.war
