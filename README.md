# zeus-report-web-docker
Dockerfile ambiente do zeus-report-web

#### Build
docker build -t seniocaires/zeus-report-web .

#### Run
docker run --name=zeusreportweb -d -p 8080:8080 -it seniocaires/zeus-report-web

#### URL
http://localhost:8080/zeus-report-web
