# Use the official Microsoft SQL Server image
FROM mcr.microsoft.com/mssql/server:2019-latest

# Set environment variables
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=YourStrong!Passw0rd
ENV MSSQL_PID=Express

# Expose SQL Server default port
EXPOSE 1433

# Start SQL Server
CMD ["/opt/mssql/bin/sqlservr"]