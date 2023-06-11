minetest blockexchange infrastructure code

[![deploy](https://github.com/blockexchange/blockexchange.minetest.land/actions/workflows/deployment.yml/badge.svg)](https://github.com/blockexchange/blockexchange.minetest.land/actions/workflows/deployment.yml)
[![validate](https://github.com/blockexchange/blockexchange.minetest.land/actions/workflows/validate.yml/badge.svg)](https://github.com/blockexchange/blockexchange.minetest.land/actions/workflows/validate.yml)

# Overview

This repository deploys the `blockexchange_server` application on its `latest` image to https://blockexchange.minetest.ch

## Manual deployment

```bash
ansible-playbook -i hosts --ask-vault-pass deploy.yml
```

## Edit secrets

```bash
ansible-vault edit blockexchange.env
```