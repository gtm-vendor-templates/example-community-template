# example-community-template
An example community template repository that can be used as a template to generate new community template repositories.

## Creating your community gallery template repository
1. Make sure you have a github account.
1. Create a new public repository using the [example template](https://github.com/gtm-vendor-templates/example-community-template).
1. Follow steps for importing your template [add link]().
1. Follow steps for publishing a new version [add link]().
1. Add the template to the gallery using the tool located on the [getting started page](https://tagmanager.google.com/gallery/getting-started).
1. Once submitted the template will go through an approval process before showing up in the gallery.

## Importing your template
1. Create a new Tag or Variable template. [Documentation](https://developers.google.com/tag-manager/templates/)
1. Once your template is complete use the export feature found in the overflow menu.
1. Locate the saved file and move it into your repository.
1. Commit and push changes to github.

## Updating the template
Once you've finalized the version you want to publish create a new version entry at the top of the versions field in the metadata.json file.

1. Once you've submitted the latest version of the template it's time to update the latest version of the file.

```json
{
    "versions": {
        {
            "changeNotes": "Added support for ecommerce",
            "sha": "bde5543"
        },
        // ...
        {
            "changeNotes": "Initial release",
            "sha": "abc1234"
        }
    }
}
```
