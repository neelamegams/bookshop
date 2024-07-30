# What to know about this repo.

This repo uses cds 8, sqliteDB, Fiori UI and app is running at https://bookshop.cfapps.eu11.hana.ondemand.com/.

    1. Used `cds` commands to create the `bookshop` app by following capire documentation
    2. Added `manifest.yml` from older working CAP project
    3. Added `sqlite` dependency in `package.json`
    4. Added `cds.server.index = true` in `package.json`
    5. Used `Fiori Application Generator` Extension on VS Code to create UI
    6. Push to CF: `cf push bookshop`
    7. Uses dev space "cf-space-shrini" in the "my Free Tier" for CF deployment.

Further enhancements expected like adding mta.yaml, app route, auth, role, scopes etc. 
Keep watching!

# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch`
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).
