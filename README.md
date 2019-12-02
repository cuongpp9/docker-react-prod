:pill: Build docker image: :clap:

==>>> Docker build -t docker-react:build-prod .

:pill: Start docker image ::clap:

==>>>> docker run -d -p 3000:80 docker-react:build-prod
