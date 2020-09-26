# ${REPO_NAME_TITLE}

${REPO_DESCRIPTION}

## Basic usage

1. Set up Docker Swarm and [`abra`]
2. Deploy [`compose-stacks/traefik`]
3. `git clone ${REPO_HTTPS_URL} && cd ${REPO_NAME}`
3. `cp .envrc.sample .envrc`
4. Edit `.envrc` - be sure to change `$DOMAIN` to something that resolves to
   your Docker swarm box
5. `direnv allow` (or `. .envrc`)
6. `abra deploy`

[`abra`]: https://git.autonomic.zone/autonomic-cooperative/abra
[`compose-stacks/traefik`]: https://git.autonomic.zone/compose-stacks/traefik
