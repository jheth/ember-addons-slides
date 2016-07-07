##  Project Structure

```text
app/               - merged with the application’s namespace.
addon/             - part of the addon’s namespace.
blueprints/        - contains any blueprints that come with the addon,
                     each in a separate directory
public/            - static files which will be available in
                     the application as /your-addon/*
test-support/      - merged with the application’s tests/
tests/             - test infrastructure including a “dummy” app and
                     acceptance test helpers.
vendor/            - vendor specific files, such as stylesheets,
                     fonts, external libs etc.
ember-cli-build.js - Compilation configuration
package.json       - Node meta-data, dependencies etc.
index.js           - main Node entry point (as per npm conventions)
```
