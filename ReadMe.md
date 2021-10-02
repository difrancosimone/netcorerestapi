Simple netcore5 rest api using EntityFramework
More info at https://docs.microsoft.com/it-it/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio

# Build docker container

docker build -t netcore-rest-api -f Dockerfile .

# Run Application

docker run -d --rm -p 5000:80 netcore-rest-api:latest

# Test running container

Point your browser to http://localhost:5000/weatherforecast