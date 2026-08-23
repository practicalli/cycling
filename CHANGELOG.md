# Changelog

## Unreleased

### Updated

- docs(equipment): 📝 update tyres description


## 2026-08-23

### Added

- build(github): 🔧 prevent jekyll build of static site during CI deployment
- docs(audax): 📝 Scottish evens in Aberdeenshire
- build(assets): 💄 admonition background and keyboard styles
- ci(actions): 📦 update to latest versions
- ci(github): 🔧 update to practicalli configuration and workflow
- ci(megalinter): 🔧 add header accept for html and json to lychee config
- ci(megalinter): 🔧 add header accept types, remove host interval
- ci(megalinter): 🔧 add packages read permission to workflow
- ci(megalinter): 🔧 allow-sentence-double-space to support typographical convention
- ci(megalinter): 🔧 apply fixes via a pull request
- ci(megalinter): 🔧 base_url for relative link check in lychee
- ci(megalinter): 🔧 enable metrics reporter
- ci(megalinter): 🔧 exclude overrides and docs-assets directories
- ci(megalinter): 🔧 extend cache and minimise retries for lychee link check
- ci(megalinter): 🔧 link to rumdl rules
- ci(megalinter): 🔧 linux firefox user agent for lychee
- ci(megalinter): 🔧 lychee configuration
- ci(megalinter): 🔧 markdown rumdl linter config
- ci(megalinter): 🔧 practicalli-johnny hosted zensical custom flavor
- ci(megalinter): 🔧 remove document flavor megalinter
- ci(megalinter): 🔧 remove markdown-rumdl atomic-spans key
- ci(megalinter): 🔧 remove markdown-rumdl keys kept at default values
- ci(megalinter): 🔧 remove markup syntax guide
- ci(megalinter): 🔧 simplified config for zensical custom flavor
- ci(megalinter): 🔧 use latest release of zensical custom flavor
- ci(megalinter): 🔧 use practicalli custom flavor for zensical
- ci(megalinter): 🔧 use practicalli zensical beta megalinter custom image
- ci(megalinter): 🔧 use practicalli zensical megalinter custom image
- ci(megalinter): 🔧 use zensical custom flavor
- docs(audax): 📝 Insch and Strathdon events in Aberdeenshire
- docs(clubs): 📝 new page with active cycling clubs
- docs(equipment): 📝 add bib shorts and update spatzwear kit reviews
- docs(equipment): 📝 update content on tyres and add in-page links for navigation
- docs(maintenance): 📝 update tyres page
- docs(readme): 📝 add link to zensical guide on practicalli engineering playbook
- docs(readme): 📝 add specific uv and zensical commands to local dev section
- docs(readme): 📝 clarify reason for uv tool install
- docs(readme): 📝 remove target blank on zensical link
- feat(zensical): use minimal syntax for section index pages
- fix(intro): remove code to show strava statistics
- fix(links): add empty URL's found via lychee linter in megalinter workflow
- fix(routes): add link for whitstable route
- style: update format of Makefile
- dev: practicalli config for lychee in megalinter workflow
- events: add brands hatch cyclothon
- dev: update docs-install description to mention theme plugin
- dev: use full name of docker image with beta tag
- dev: try beta tag with megalinter custom flavor
- dev: mega-linter-runner generated mega-linter workflow
- dev: use practicalli repository for custom megalinter falvor
- dev: update practicalli custom megalinter flavor for zensical from docker
- equipment: add bianchi, ribble, gusto and sunpeed bike images
- equipment: enhance wording on fuel page in several sections
- equipment: add lobo image to water bladder section in fuel page
- equipment: add electrolyte information and image to fuel page
- nav: move bike-fit next to choosing a bike page
- nav: remove previous flat navigation definition
- equipment: add drop definition to handlebars section
- equipment: add brands and where to by section to choosing a bike page
- equipment: thinvik zarmor zephyr tyre alternative to gp500
- dev: use practicalli custom megalinter flavor for zensical
- dev: update syntax for conditional to upload megalinter artifacts
- dev: update github workflows to checkout v7 action
- equipment: started page on fuel
- events: plans for team rocket rides
- events: start multi-day events page
- events: additional events discovered
- equipment: add further content to clothes, update links
- events: update headings in lands end experience report
- nav: section names for index files
- nav: update curated routes and experiences locations
- equipment: kit reviews page with spatzwear kit
- equipment: complete choosing a bike page
- equipment: minor changes for clarity
- dev: fix description of website
- fix(links): update links after refactor of naviation
- refactor: reorganise sections for greater discovery
- events: start adding UK sportive details
- dev: add catppuccin theme to zensical config
- fix(links): update hyperlinks with help from zensical studio
- dev: add catppuccin-zensical theme to zensical build workflow
- dev: update zensical config to use catppuccin-zensical theme and toggles
- dev: add catppuccin-zensical theme to zensical install
- bicycle-components: add frame geometry to bike-fit
- bicycle-components: update bike-fit wording
- dev: set docs as root for marksman lsp
- dev: run only after megalinter completed and paths match
- dev: configure on paths to run only when specified files change
- training: add June tapering and rest week to training plan
- components: added videos to tubeless tyre section
- maintenance: started section on tyres
- components: add links to shoe manufacturers & note on shoe design
- dev: ignore github config for lychee spell check in megalinter
- dev: megalinter config updated via makefile task
- dev: fix paths config - wrong indentation
- nav: fix maintenance paths
- content: standard practicalli overrides
- design: add standard assets for practicalli books
- format: tidy readme
- dev: update makefile with legacy mkdocs task
- dev: update doc publish workflow
- dev: practicalli github workflows and config
- zensical: admonition code examples
- dev: include list of default plugins
- zensical: example code for buttons
- dev: update GitHub actions via `make dependencies-update`

### Updated

- dev: update GitHub actions via `make dependencies-update`

| :file                      | :name                         | :current | :latest |
|----------------------------|-------------------------------|----------|---------|
| .github/workflows/docs.yml | actions/checkout              | v5       | v6.0.2  |
|                            | actions/configure-pages       | v5       | v6      |
|                            | actions/deploy-pages          | v4       | v5      |
|                            | actions/setup-python          | v5       | v6.2.0  |
|                            | actions/upload-pages-artifact | v4       | v5.0.0  |
