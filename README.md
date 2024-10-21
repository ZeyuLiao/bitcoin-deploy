[![Deploy on Push to Main](https://github.com/ZeyuLiao/bitcoin-deploy/actions/workflows/deploy.yml/badge.svg)](https://github.com/ZeyuLiao/bitcoin-deploy/actions/workflows/deploy.yml)

# bitcoin-deploy
Docker Compose deploy for bitcoin back-end and ingestion program

## RELEASE

The only thing you need to do is updating the image version in the [docker-compose.yaml](./docker-compose.yaml)
Once completed, just push to the main branch or merge PR to main branch, these will trigger [Github Action](https://github.com/ZeyuLiao/bitcoin-deploy/actions) to automatically deploy project to the remote cloud platfrom.