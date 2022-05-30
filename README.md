# This repo is used for creating images used by my personal k8s cluster for hosting mc servers

curseforge images need to be built manually due to modpacks being to large for source control.

to build the curseforge image manually and push to docker-hub:
`docker build . -t imkumpy/curseforge-mc:main`
`docker push imkumpy/curseforge-mc:main`
