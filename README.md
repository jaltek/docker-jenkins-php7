# docker-jenkins-php7
Docker image based on the [official jenkins docker image](https://github.com/jenkinsci/docker) and the php template from [jenkins-php.org](jenkins-php.org).

# Configuration of the image
This image uses **PHP 7.0** from the [PPA by Ondřej Surý](https://launchpad.net/~ondrej/+archive/ubuntu/php)

# Using

To use this container simply pull it from the docker repository:

```docker pull jaltek/docker-jenkins-php7```

followed by

```docker run -p 8080:8080 -p 50000:50000 jaltek/docker-jenkins-php7```


# Thanks to
This image is inspired by and mainly based on [iliyan-trifonov/jenkins-ci-php](https://github.com/iliyan-trifonov/jenkins-ci-php)

