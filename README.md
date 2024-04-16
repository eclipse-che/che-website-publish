# Eclipse Che static website

A worklow runs on schedule, daily at 5:30 and 17:30, and might be run manually, and do following steps:

1. Get che-website sources.
2. Build che-website static site.
3. Get che-docs content publication branch.
4. Copy docs to the built website.
5. Push the results to the publish branch.
