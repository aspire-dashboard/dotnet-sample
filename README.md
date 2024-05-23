# Aspire Dashboard ♥️ .NET

To run the Aspire Dashboard first run:

```cli
docker run --rm -it -p 18888:18888 -p 4317:18889 -d --name aspire-dashboard \
    mcr.microsoft.com/dotnet/aspire-dashboard:8.0.0
```

Locate the dashboard url and api key with the following Docker command (replace 0.0.0.0 with localhost):

```cli
docker logs aspire-dashboard
```

To run this application:

```cli
dotnet run
```
