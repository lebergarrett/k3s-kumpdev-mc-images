# This repo is used for creating images used by my personal k8s cluster for hosting mc servers

(note: ftb-fabric is not restricted to ftb packs, it's actually primarily used for curseforge packs here) ftb-fabric images need to be built manually due to modpacks being to large for source control.

to build the ftb-fabric image manually and push to docker-hub:
`docker build . -t imkumpy/ftb-fabric-mc:main`
`docker push imkumpy/ftb-fabric-mc:main`
