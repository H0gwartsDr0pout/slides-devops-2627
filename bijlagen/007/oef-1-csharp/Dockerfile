FROM mcr.microsoft.com/dotnet/sdk:8.0
CMD ["sleep", "infinity"]
WORKDIR /app
COPY ./app .
RUN dotnet build
CMD ["dotnet", "run"]
