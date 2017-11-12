FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 8083
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "AllMusic.Stream.API.dll"]
