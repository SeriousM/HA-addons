# Example Home Assistant add-on repository

This repository can be used as a "blueprint" for add-on development to help you get started.

Add-on documentation: <https://developers.home-assistant.io/docs/add-ons>

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FL0rdShrek%2FHA-addons)

_Example add-on to use as a blueprint for new add-ons._
### [n8n](./n8n)
![Supports amd64 Architecture][amd64-shield]

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg

_The workflow automation platform that doesn't box you in, that you never outgrow._


### [snowflake](./snowflake)
![Supports amd64 Architecture][amd64-shield]

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg

_Snowflake is a system that **allows people from all over the world to access censored websites and applications**._

### [searxng](./searxng)


### [AFFiNE](./AFFiNE)

<!--
Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->