# README #

This repository contains the content for the Currencycloud Open Banking developer portal. This portal
will primarily be used by third party developers (TPP developers) to consume the Open Banking APIs
exposed by Ozone, for Currencycloud.

This repository can be used to tailor the content presented to the third party developers including
branding.

### How this repository is used ###

This repository is pulled by ozone and used to refresh the content being displayed on the developer portal.
The developer portal is maintained by ozone, this repository provides the content to be displayed on the portal.

* The UK portal content is served from the `uk-docs-release` branch
* The EU portal content is served from the `eu-docs-release` branch

Any updates to the documentation should be made in the master branch.

If the API spec is changed, it is expected to update the swagger definitions checked into this repository.