# docker-helm
Docker image containing kubernetes helm.

The image is based on alpine.

Usage: `docker run kube-aws/helm`

# Acknowledgement

Thanks to [linkyard/docker-helm](https://github.com/linkyard/docker-helm) for the original implementation.
The only differences of kube-aws/helm from the original linkyard/helm would be the author info included the image and the removal of git from the image(kube-aws didn't require git in a helm image).
