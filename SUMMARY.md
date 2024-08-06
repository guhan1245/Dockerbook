# Table of Content

* [Introduction to Containerization and Docker](introduction-to-containerization-and-docker.md)
* [Installing Docker](installing-docker/README.md)
    * [Installation on macOS](installing-docker/README.md#installation-on-macos)
    * [Installation on Windows](installing-docker/README.md#installation-on-windows)
    * [Installation on Linux](installing-docker/README.md#installation-on-linux)
* [Hello World in Docker](hello-world-in-docker/README.md)
    * [Container](hello-world-in-docker/README.md#container)
    * [Image](hello-world-in-docker/README.md#image)
    * [Registry](hello-world-in-docker/README.md#registry)
    * [Docker Architecture](hello-world-in-docker/README.md#docker-architecture)
    * [The Full Picture](hello-world-in-docker/README.md#the-full-picture)
* [Container Manipulation Basics](container-manipulation-basics/README.md)
    * [Running Containers](container-manipulation-basics/README.md#running-containers)
    * [Publishing Ports](container-manipulation-basics/README.md#publishing-ports)
    * [Detached Mode](container-manipulation-basics/README.md#detached-mode)
    * [Listing Containers](container-manipulation-basics/README.md#listing-containers)
    * [Naming or Renaming Containers](container-manipulation-basics/README.md#naming-or-renaming-containers)
    * [Stopping or Killing a Running Container](container-manipulation-basics/README.md#stopping-or-killing-a-running-container)
    * [Restarting Containers](container-manipulation-basics/README.md#restarting-containers)
    * [Creating Containers Without Running](container-manipulation-basics/README.md#creating-containers-without-running)
    * [Removing Dangling Containers](container-manipulation-basics/README.md#removing-dangling-containers)
    * [Running Containers in Interactive Mode](container-manipulation-basics/README.md#running-containers-in-interactive-mode)
    * [Executing Commands Inside a Container](container-manipulation-basics/README.md#executing-commands-inside-a-container)
    * [Working With Executable Images](container-manipulation-basics/README.md#working-with-executable-images)
* [Image Manipulation Basics](image-manipulation-basics/README.md)
    * [Image Creation Basics](image-manipulation-basics/README.md#image-creation-basics)
    * [Tagging Images](image-manipulation-basics/README.md#tagging-images)
    * [Listing and Removing Images](image-manipulation-basics/README.md#listing-and-removing-images)
    * [Understanding the Many Layers of an Image](image-manipulation-basics/README.md#understanding-the-many-layers-of-an-image)
    * [Building NGINX From Source](image-manipulation-basics/README.md#building-nginx-from-source)
    * [Optimizing Images](image-manipulation-basics/README.md#optimizing-images)
    * [Embracing Alpine Linux](image-manipulation-basics/README.md#embracing-alpine-linux)
    * [Creating Executable Images](image-manipulation-basics/README.md#creating-executable-images)
    * [Sharing Your Images Online](image-manipulation-basics/README.md#sharing-your-images-online)
* [Containerizing a JavaScript Application](containerizing-a-javascript-application/README.md)
    * [Writing The Development Dockerfile](containerizing-a-javascript-application/README.md#writing-the-development-dockerfile)
    * [Working With Bind Mounts](containerizing-a-javascript-application/README.md#working-with-bind-mounts)
    * [Working With Anonymous Volumes](containerizing-a-javascript-application/README.md#working-with-anonymous-volumes)
    * [Performing Multi-Staged Builds](containerizing-a-javascript-application/README.md#performing-multi-staged-builds)
    * [Ignoring Unnecessary Files](containerizing-a-javascript-application/README.md#ignoring-unnecessary-files)
* [Network Manipulation Basics](network-manipulation-basics.md)
    * [Network Basics](network-manipulation-basics.md#network-basics)
    * [Creating a User-Defined Bridge](network-manipulation-basics.md#creating-a-user-defined-bridge)
    * [Attaching Containers to a Network](network-manipulation-basics.md#attaching-containers-to-a-network)
    * [Detaching Containers from a Network](network-manipulation-basics.md#detaching-containers-from-a-network)
    * [Getting Rid of Networks](network-manipulation-basics.md#getting-rid-of-networks)
* [Containerizing a Multi-Container JavaScript Application](containerizing-a-multi-container-javascript-application/README.md)
    * [Setting Up The Custom Bridge Network](containerizing-a-multi-container-javascript-application/README.md#setting-up-the-custom-bridge-network)
    * [Running the Database Server](containerizing-a-multi-container-javascript-application/README.md#running-the-database-server)
    * [Working With Named Volumes](containerizing-a-multi-container-javascript-application/README.md#working-with-named-volumes)
    * [Accessing Logs From a Container](containerizing-a-multi-container-javascript-application/README.md#accessing-logs-from-a-container)
    * [Attaching The Database Server (in case you missed it earlier)](containerizing-a-multi-container-javascript-application/README.md#attaching-the-database-server-in-case-you-missed-it-earlier)
    * [Writing The Dockerfile)](containerizing-a-multi-container-javascript-application/README.md#writing-the-dockerfile)
    * [Executing Commands in a Running Container)](containerizing-a-multi-container-javascript-application/README.md#executing-commands-in-a-running-container)
    * [Writing Management Scripts)](containerizing-a-multi-container-javascript-application/README.md#writing-management-scripts)
* [Composing Projects Using Docker-Compose](composing-projects-using-docker-compose/README.md)
    * [Compose Basics](composing-projects-using-docker-compose/README.md#compose-basics)
    * [What About the Network Bridge?](composing-projects-using-docker-compose/README.md#what-about-the-network-bridge)
    * [Starting Services](composing-projects-using-docker-compose/README.md#starting-services)
    * [Listing Services](composing-projects-using-docker-compose/README.md#listing-services)
    * [Executing Commands Inside a Running Service](composing-projects-using-docker-compose/README.md#executing-commands-inside-a-running-service)
    * [Accessing Logs From a Running Service](composing-projects-using-docker-compose/README.md#accessing-logs-from-a-running-service)
    * [Stopping Services](composing-projects-using-docker-compose/README.md#stopping-services)
    * [Composing a Full-stack Application](composing-projects-using-docker-compose/README.md#composing-a-full-stack-application)
* [Conclusion](conclusion.md)