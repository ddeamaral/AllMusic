FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 8084
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "AllMusic.Account.API.dll"]
