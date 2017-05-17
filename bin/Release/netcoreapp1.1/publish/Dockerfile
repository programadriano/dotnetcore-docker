FROM microsoft/dotnet:1.1.1-runtime

WORKDIR /app  
COPY . .

CMD ASPNETCORE_URLS=http://*:$PORT dotnet hello-aspnet.dll