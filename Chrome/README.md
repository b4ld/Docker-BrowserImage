
# Chrome Images to Selenium Usage

## Getting Started

This is a repository that Aims to make the connection between Browsers Version relieses, and the DockerHub Image.
This intend to help with Selenium and Docker to Web browser testing.

### Get .deb Files From Repository

*If you want to mount your own docker images:*

**Google Chrome Verion**

Here you can Download .deb files for Google Chrome.

#Chrome V49.0.2623.75
https://mega.nz/#!J4ZB3S6Z!fmB2yZFsC_wPbCJFPbVAgNbBqqXG0bE-3AI9Na5Yipo






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
image: b4lddocker/browserimage:v36.0.1985.143-1
```


You can see more examples here:(link)


### Docker Hub Repository

[DokerHub Chrome Images Repository](https://hub.docker.com/r/b4lddocker/browser-chrome)




