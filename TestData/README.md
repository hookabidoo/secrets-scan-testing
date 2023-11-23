# aspnetcore-scan-testing

[![.NET](https://github.com/damienbod/aspnetcore-scan-testing/actions/workflows/dotnet-gitguardian.yml/badge.svg)](https://github.com/damienbod/aspnetcore-scan-testing/actions/workflows/dotnet-gitguardian.yml)

[![.NET](https://github.com/damienbod/aspnetcore-scan-testing/actions/workflows/dotnet-gitleaks.yml/badge.svg)](https://github.com/damienbod/aspnetcore-scan-testing/actions/workflows/dotnet-gitleaks.yml)

## secrets added to the appsettings.json
{
   "ConnectionStrings": {
    "DefaultConnection": "Data Source=.\\SQLEXPRESS;Initial Catalog=FilesDescriptionAzureStorage;Integrated Security=True;Connect Timeout=30;Encrypt=False;TrustServerCertificate=False;ApplicationIntent=ReadWrite;MultiSubnetFailover=False",
    "AzureServiceBus": "Endpoint=sb://test.servicebus.windows.net/;SharedAccessKeyName=RootManageSharedAccessKey;SharedAccessKey=h1fdfdgfjnhmcvbtz65h65hn6hgeb"
  },
  "AzureAd": {
    "ClientSecret": "vvfgfhghgjw4tgrgfbgfhgfjsrt",
  },
  "ApiTwo": {
    "accessToken": "eygregertg4ert3gtrhzi76gfnghmjhmjhmdfrsfreterhgfndghvbfvb"
  },
  "MyBotSecrets": {
    "ApiKey": "Yp9B3$7i6epJbuUfOcgC"
  },
  "ApiTwo": {
    "password": "secretFiPass"
  }
}

## Links
https://github.com/GitGuardian/ggshield
https://dashboard.gitguardian.com/workspace/142648/perimeter?health=_&sort_health=true&sort_ic=true
https://github.com/zricethezav/gitleaks
https://codeql.github.com/docs/
