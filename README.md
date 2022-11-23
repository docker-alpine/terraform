# AWS cli EKS with Terraform  

## Built With  

* kubectl 1.24.4
* Terraform 1.3.4
* Helm 3.10.2
* kustomize 4.5.7
* eks 0.120
* awscli
* kubeseal 0.19.1
* Kubernetes Sigs 0.5.9

### Prerequisities


In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

#### Container Run

```shell
docker run terraformaws/eks:latest terraform version
```

Run kubectl

```shell
docker run terraformaws/eks:latest kubectl version --output=yaml
```

## Find Us

* [GitHub](https://github.com/docker-alpine/terraform)

## Authors

* **Dmitry Popov** - *Initial work* - [popov-do](https://github.com/popov-do)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* People you want to thank
* If you took a bunch of code from somewhere list it here
