FROM mcr.microsoft.com/dotnet/aspnet:3.1
COPY https https
COPY bin/Release/netcoreapp3.1/publish App/
WORKDIR /App
ENTRYPOINT ["dotnet", "Api.dll"]