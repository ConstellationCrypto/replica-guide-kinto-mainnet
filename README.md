# Running a Replica node

This repo is setup to easily run Kinto mainnet replica nodes. Simply run `docker-compose up` to bring a Kinto mainnet replica node up locally.

Note: you'll need to supply an endpoint for an Ethereum beacon API endpoint.

The docker image for Kinto mainnet is hosted in a public ECR repo: `public.ecr.aws/i6b2w2n6/nitro-node:kinto-mainnet-10.0.0`

The nodeConfig file is prepopulated with Kinto mainnet parameters. The current setup uses a public rpc url for the Ethereum mainnet rpc and stores node data in docker volume.
