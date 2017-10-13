FROM microsoft/aspnetcore:2.0
ARG source
ENV AIKey="11111111-2222-3333-4444-555555555555"
ENV Slot="debug"
WORKDIR /app
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "DockerWebApp.dll"]
