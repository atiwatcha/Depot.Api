# Depot.Api
web dotnet for linux
sudo -i 

ubutu 14.04 ltf
dotnet new mvc
dotnet restore
dotnet run

docker build -t weblinux-demo .
docker run -p 5000:5000 weblinux-demo:1.0

--push repositories
ex:docker tag imageID Repositoryname 
docker tag weblinux-demo atiwatc/weblinux:1.0
docker tag depot.api-demo atiwatc/webdotnet:1.0

ex:docker push Repositoryname 
docker push atiwatc/weblinux:1.0

docker pull atiwatc/weblinux:1.0

sudo -i
sudo netstat -tlnp
