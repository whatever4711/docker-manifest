# docker-manifest

https://github.com/docker/cli/pull/138

Early build of the docker cli which includes manifest functinality

Usage:	`docker run  -v /var/run/docker.sock:/var/run/docker.sock --rm project31/docker-manifest /bin/bash -c 'docker manifest COMMAND'`

Manage Docker image manifests and manifest lists

...
Options:
      --help   Print usage

Commands:
  annotate    Add additional information to a local image manifest
  create      Create a local manifest list for annotating and pushing to a registry
  inspect     Display an image manifest, or manifest list
  push        Push a manifest list to a repository
...

Run `docker run  -v /var/run/docker.sock:/var/run/docker.sock --rm project31/docker-manifest /bin/bash -c 'docker manifest COMMAND --help` for more information on a command.
