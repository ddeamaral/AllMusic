FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 8082
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "AllMusic.Lyrics.API.dll"]
