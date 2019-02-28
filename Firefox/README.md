# Chrome Images to Selenium Usage

## Getting Started

This is a repository that Aims to make the connection between Browsers Version relieses, and the DockerHub Image.
This intend to help with Selenium and Docker to Web browser testing.

### Get .deb Files From Repository

*If you want to mount your own docker images:*

**Google Chrome Verion**

Here you can Download .deb files for Google Chrome.

(links)




### Prerequisites

This images ar all tested with Selenium v3.5.

Some Older versions can encounter issius os compatibility.


### Working with Docker Hub

On you Docker-Compose file:


```
image: b4lddocker/browserimage:[browserVersion]
```


Example:
```
image: b4lddocker/browserimage:chromeV36.0.1985.143-1
```


You can see more examples here:(link)


### Docker Hub Repository

[DokerHub](https://hub.docker.com/r/b4lddocker/browser-firefox)




## Versioning

*Version 0.0.1
For the versions available, see the [tags on this repository](https://github.com/). 

## Authors

* **Pedro Carmezim** - *Initial work* - [GitHubRepo](https://github.com/b4ld)
* **Josue Rocha** - *Initial work* - [GitHubRepo](https://github.com/JosueRocha24)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details




