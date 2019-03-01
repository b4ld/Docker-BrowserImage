# Chrome Images to Selenium Usage

## Getting Started

This is a repository that Aims to make the connection between Browsers Version relieses, and the DockerHub Image.
This intend to help with Selenium and Docker to Web browser testing.


***

### Get .deb Files From Repository

*If you want to mount your own docker images:*

-- [Firefox_V65.0.1-1](https://mega.nz/#!Uh521aAA!gNo9h6rYKBgJtOs66e8y6FOEjwxz0hMinkmf2HPTu18)


**Google Chrome Version**

Here you can Download .deb files for Mozzila FireFox.

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
image: b4lddocker/browserimage:firefoxV65.0.1-1
```


You can see more examples here:(link)


### Docker Hub Repository

[DokerHub Images Firefox Repository](https://hub.docker.com/r/b4lddocker/browser-firefox)







