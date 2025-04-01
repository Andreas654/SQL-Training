# Verwenden Sie ein Basisimage mit einer SQL-Datenbank
FROM mcr.microsoft.com/mssql/server:2022-latest

# Setzen Sie Umgebungsvariablen
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=YourStrong!Passw0rd

# Öffnen Sie den SQL-Server-Port
EXPOSE 1433

# Starten Sie den SQL-Server
CMD /opt/mssql/bin/sqlservr
