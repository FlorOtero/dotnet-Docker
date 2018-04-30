FROM microsoft/dotnet:2.0-sdk
COPY . /app
WORKDIR /app
RUN ["dotnet", "restore"]
EXPOSE 5000/tcp
ENTRYPOINT ["dotnet", "run", "--server.urls", "http://0.0.0.0:5000"]
