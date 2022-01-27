# GraphCMS UI Extension Demo - Visibility Toggle

[Join our Slack](https://slack.graphcms.com)

With this example UI Extention, you can add a toggle field to a GraphCMS model that set the visibility for other fields in the model.

## How to Use

### Download Manually

The code for this example can be downloaded with the following command:

```bash
npx degit gijshendrix/uix-visibility-toggle uix-visibility-toggle
```

Deploy the code to Vercel, Netlify, GitHub Pages, or run locally. Next, install on GraphCMS as a UI extension using the URL to your index page as the URL for your extension.

For testing purposes, you can also use the Github Pages url for this repository: `https://gijshendrix.github.io/uix-visibility-toggle/`

### Add field to model and configure

Add the Field Visibility Toggle to one of your models. In the 'Create field' dialog, you'll be asked to provide the apiIDs of the fields for which you want to toggle the visibility in a comma-separated string. Make sure these fields are hidden by default, by setting their field visibility to 'Hidden' in the Advanced tab of the field settings dialog. The toggle will override this setting when editing a content entry. Although not required, it's suggested to sort the fields in your model in such a way that the toggle is directly above the fields that will have their visibility toggled.

## Going further

- [GraphCMS UI Extensions Documentation](https://graphcms.com/docs/ui-extensions)
