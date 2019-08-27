# example-community-template

An example community template repository that can be used as a template to
generate new community template repositories.

## Creating your community gallery template repository

1.  Make sure you have a github account.
1.  Create a new public repository using the
    [example template](https://github.com/gtm-vendor-templates/example-community-template).
1.  Follow steps for [importing your template](#importing-your-template).
1.  Follow steps for publishing a new version [add link]().
1.  Add the template to the gallery using the tool located on the
    [getting started page](https://tagmanager.google.com/gallery/getting-started).
1.  Once submitted the template will go through an approval process before
    showing up in the gallery.

## Importing your template

1.  Create a new Tag or Variable template.
    [Documentation](https://developers.google.com/tag-manager/templates/)
1.  Once your template is complete use the export feature found in the overflow
    menu.
1.  Locate the saved file and move it into your repository.
1.  Rename the file to `template.tpl`.
1.  Commit and push changes to github.
1.  Follow steps for [publishing a new version](#publishing-a-new-version-to-the-community-gallery).

## Publishing a new version to the Community Gallery

1. Locate the commit that includes the changes that you want to push. An easy way to do this is by looking at the commits page.
1. Once you've located the commit copy the change number/sha.
1. Now add a new entry to the top of the versions list in metadata.yaml.
  ```yaml
  versions:
    # Add new version at the top
    - sha: bde5543
      changeNotes: Added support for ecommerce
    # Older Versions
    - sha: bde5543
    - sha: abc1234
      changeNotes: Initial release
  ```
1. Commit the change to metadata.yaml and your update will appear in the gallery typically within 24 hours.
