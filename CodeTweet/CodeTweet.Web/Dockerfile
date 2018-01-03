FROM microsoft/aspnetcore:1.1
WORKDIR /app
COPY ./publish/* /app/
ENTRYPOINT ["dotnet", "/app/CodeTweet.Web.dll"]
