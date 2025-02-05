# Ubuntu Docker Image

[**DockerHub Repository Link**](https://hub.docker.com/repository/docker/registryhj/ubuntu/general)

<br />

## Supported Tags

- [`24.04`](https://hub.docker.com/repository/docker/registryhj/ubuntu/tags/24.04/sha256-66cf001708ca2470b672dd93622e5e5eb71451e445adfe1b6e103fea39ea51b8): (`24.04.1`, `noble`)
- [`22.04`](https://hub.docker.com/repository/docker/registryhj/ubuntu/tags/22.04/sha256-fba2ac169c936e51e218dce9c967e0250bab5d86dcf915a3e13c112c1b06b7a2): (`22.04.5`, `jammy`)
- [`20.04`](https://hub.docker.com/repository/docker/registryhj/ubuntu/tags/20.04/sha256-15305374f54c68b6e7b31e341b31c2444b2dd111cf831a0febca6669a00d09b6): (`20.04.5`, `focal`)

<br />

## How to use

**Pull this image:**

```
docker pull registryhj/ubuntu:<tag_name>
```

**Create container in background process:**

```
docker run -d -it --name <container_name> registryhj/ubuntu:<tag_name>
```

**Execute Shell Prompt:**

```
docker exec -it <container_name> zsh
```

<br />

## Supported Architectures

- `linux/amd64`
- `linux/arm64`

# <br />

Copyright © 2025 RegistryHJ
