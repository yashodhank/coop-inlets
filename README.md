# ${REPO_NAME_TITLE}

${REPO_DESCRIPTION}

## Basic usage

1. Set up Docker Swarm and [`abra`]
2. Deploy [`coop-cloud/traefik`]
3. `abra app new ${REPO_NAME} --secrets`
4. `abra app YOURAPPDOMAIN config` - be sure to change `$DOMAIN` to something that resolves to
   your Docker swarm box
5. `abra app YOURAPPDOMAIN deploy`
6. Open the configured domain in your browser to finish set-up

[`abra`]: https://git.autonomic.zone/autonomic-cooperative/abra
[`coop-cloud/traefik`]: https://git.autonomic.zone/coop-cloud/traefik
