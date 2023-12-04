<img src="https://github.com/cloudproud/lab/assets/3440116/9a92844f-15a6-45a1-9f75-5f26b56b8ee8" width="250px" alt="Cloud Proud" />

# Lab

The lab repository contains releases for the latest versions of kit.
You could download and install kit & kitctl by downloading one of the binaries from one of the releases or using the shell script below.

```sh
$ # The following script will install kit & kitctl in ./bin
$ https://raw.githubusercontent.com/cloudproud/lab/main/install.sh | sh
```

> 🚧 Check out our [documentation](https://cloudproud.dev/docs) for more information!

---

```sh
$ kit --insecure
$ # The web interface is up and running at: http://localhost:5432
$ # You could login using the default username and password kit:kitpw
```

## Docker images

It is possible to download and run `kit` within a docker container.
This will spin up a single-node cluster which could be used for testing and/or development purposes.
You could login into this instance using the default username and password.
Check out the [documentation](https://cloudproud.dev/docs/quickstart) for more information!

```sh
$ docker run -p 5432:5432 registry.cloudproud.nl/lab/kit
$ # The web interface is up and running at: http://localhost:5432
$ # You could login using the default username and password kit:kitpw
```