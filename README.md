[![Varbase](https://raw.githubusercontent.com/Vardot/varbase/11.0.x/images/varbase-logo.png)](https://www.drupal.org/project/varbase)

# Varbase API Base

A recipe to set up JSON:API with authentication, authorization, and OpenAPI documentation for easy content ingestion by other applications.

This recipe provides the base API functionality, allowing you to easily set up a complete API infrastructure for your Drupal site.

## Features

- JSON:API for structured content access
- OAuth 2.0 authentication via Simple OAuth
- OpenAPI documentation with Redoc and Swagger UI
- JSON:API Extras for customization
- REST UI for managing REST resources
- Pre-configured API settings

## Installation

Add the recipe using composer:
```
composer require drupal/varbase_api_base:~1.0.0
```

Change directory to `/web` or `/docroot`

Run the Drupal recipe bash script:
```
bash core/scripts/drupal recipe recipes/contrib/varbase_api_base
```

or

Run the Drush recipe command:
```
drush recipe recipes/contrib/varbase_api_base
```

## Use With [Varbase](https://www.drupal.org/project/varbase) Distribution

This recipe is best used with [Varbase](https://www.drupal.org/project/varbase) distribution.

Can be installed with any Drupal site, even if installed with the Minimal or Standard profile.
However, using it with [Varbase](https://www.drupal.org/project/varbase) gives you way much more cool stuff!

## [Varbase documentation](https://docs.varbase.vardot.com/)

Check out Varbase documentation for more details.

Join Our Slack Team for Feedback and Support
http://slack.varbase.vardot.com/

This recipe is sponsored and developed by [Vardot](https://www.drupal.org/vardot).
