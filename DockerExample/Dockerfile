FROM mcr.microsoft.com/dotnet/core/aspnet:3.1 AS base
EXPOSE 80
EXPOSE 443
WORKDIR /app
COPY ["/publish", "/app"]
ENTRYPOINT ["dotnet", "DockerExample.dll"]