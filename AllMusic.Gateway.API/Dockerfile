FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 8081
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "AllMusic.Gateway.API.dll"]
