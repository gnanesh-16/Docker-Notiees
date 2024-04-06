---
description: >-
  A Complete Hands-on Docker Commands that actually Master Docker with this
  essential cheat sheet! Whether you're experienced or new to containers, it's
  your go-to for all Docker tasks.
cover: .gitbook/assets/img1.png
coverY: 0
---

# 🪬 Docker sheet

## <mark style="color:purple;">`ABOUT`</mark>                                              &#x20;

Docker commands are essential for managing Docker containers and images. With `docker run`, you can start a new container, whereas `docker ps` lists all running containers. To stop a container, use `docker stop`, followed by the container ID or name. For managing images, `docker images` displays all available images on your system, and `docker pull` downloads an image from Docker Hub. Understanding and utilizing these commands effectively can greatly enhance your Docker experience, allowing for efficient container management and deployment.



## <mark style="color:purple;">`COMMANDS`</mark>                                        &#x20;

* [ ] [_**Docker images**_](#user-content-fn-1)[^1]

<pre class="language-docker" data-title="Frequently used Commands in DOcker " data-line-numbers><code class="lang-docker">docker -t build image_name path_to_dockerfile
<strong>docker -t build appg .
</strong><strong>docker images 
</strong><strong>docker images ls 
</strong><strong>docker pull ngix:latest 
</strong><strong>docker rmi appg:latest
</strong>docker tag appg:latest appg:v1
docker push appg:v1 
docker inspect appg:v1 
docker -o save appg.tar appg:v1
docker -i load image_name.tar // appg 
docker prune //prune unsed images 
</code></pre>

[^1]: a Complete Frequently used Commands on Images-docker&#x20;
