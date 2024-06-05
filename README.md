# Eclipse Che static website

A worklow runs on schedule, daily at 5:30 and 17:30, and might be run manually, and do following steps:

1. Get che-website sources. Che website resources are taken from the `main` branch.
2. Build che-website static site.
3. Get che-docs content publication branch. See [the document](https://github.com/eclipse-che/che-docs/blob/publication-builder/README.adoc) on how che-docs publication branch is managed
4. Copy docs to the built website.
5. Push the results to the publish branch.

Eclipse Tooling will then take care of updating the website, accessible at https://eclipse.dev/che . If there are problems, create an issue at [Eclipse Helpdesk](https://gitlab.eclipse.org/eclipsefdn/helpdesk/-/issues)