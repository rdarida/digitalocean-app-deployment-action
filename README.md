<h1 align="center">digitalocean-app-deployment-action</h1>
<h3 align="center">GitHub Action for Creating an App Deployment via DigitalOcean API</h3>
<hr>

## Usage

```
name: DigitalOcean App Deploy

on:
  push:
    branches:
      - main

jobs:
  digitalocean_app_deploy:
    runs-on: ubuntu-latest
    steps:
      - name: DigitalOcean App Deployment Action
        uses: rdarida/digitalocean-app-deployment-action@v1.0.0
        with:
          token: ${{ secrets.DIGITALOCEAN_TOKEN }}
          appId: ${{ secrets.DIGITALOCEAN_APPID }}

```

<hr>
<details>
  <summary>
    <strong>Resources</strong>
  </summary>

  - Add resources here
</details>
<hr>

<p align="center">
  See license <a href="LICENSE">here</a>.
</p>
