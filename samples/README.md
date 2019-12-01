# .NET Core Docker Samples

These samples demonstrate how to use .NET Core and Docker together, for development,testing and production. You can use the samples as the basis of your own Docker images or just to learn.

* [Build a .NET Core Docker image](dotnetapp/README.md)
* [Build an ASP.NET Core Docker image](aspnetapp/README.md)
* [Build in a container](build-in-container.md)
* [Unit test in a container](unit-testing-in-container.md)
* [Develop .NET Core applications in a container](dev-in-container.md)
* [Develop ASP.NET Core Applications with Docker and HTTPS](aspnetcore-https-development.md)
* [Host ASP.NET Core Images with Docker and HTTPS](aspnetcore-https.md)
* [Push Docker Images to Azure Container Registry](push-image-to-acr.md)
* [Push Docker Images to DockerHub](push-image-to-dockerhub.md)
* [Deploy ASP.NET Core Applications to Azure Container Instances](deploy-container-to-aci.md)

## Try a pre-built .NET Core Docker Image

The following command will run a .NET Core console app in a container:

```console
docker run --rm mcr.microsoft.com/dotnet/core/samples
```

The following command will run an ASP.NET Core console app in a container that you can access in your web browser at `http://localhost:8000`.

```console
docker run --rm -it -p 8000:80 mcr.microsoft.com/dotnet/core/samples:aspnetapp
```

## Docker Repositories

You can find .NET container images at the following Docker repositories:

* [dotnet/core](https://hub.docker.com/_/microsoft-dotnet-core/): .NET Core
* [dotnet/framework](https://hub.docker.com/_/microsoft-dotnet-framework/): .NET Framework
