# Command line shortcuts

## ☕️ homebrew
- Check homebrew path: `brew --prefix`

## nginx
- Restart nginx: `nginx -s reload`

## dnsmasq
- Test if scripts are valid: `dnsmasq --test`
- Start dnsmasq: `sudo dnsmasq`

## docker
- List all running machines: `docker ps`
- Enter a machine interactively to see env variables: `docker exec -it ${containerName} bash`
- Stop a container: `docker stop ${containerName}`
- Delete a container: `docker rm ${containerName}`

## linux
- Listen to logs: `tail -f /path/to/file`
