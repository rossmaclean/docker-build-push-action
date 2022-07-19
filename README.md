# Docker Build Push Action
This actions builds a Docker image and pushes it to Dockerhub.

## Arguments
### Docker User
- **Key**: docker-user
- **Required**: true

The user which will be used when building/pushing the image.

### Image Name
- **Key**: image-name
- **Required**: true

The image name which will be used when building/pushing the image

### Dockerhub Token
 - **Key**: dockerhub-token
 - **Required**: true

The token used to push the image.

### Version
- **Key**: version
- **Required**: true

The version used when building/pushing the image.

**NOTE**: The tag `latest` is also added to all images.