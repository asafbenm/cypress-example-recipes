# Interacting with iframes

This recipe shows how to:

- Access elements inside an iframe coming from 3rd party domain
- Spy on `window.fetch` calls from the iframe
- Stub network calls coming from the iframe

<!-- TODO add link to the blog post -->

Spec | Description
--- | ---
[first-spec.js](cypress/integration/first-spec.js) | Loads the [index.html](index.html)
[button-spec.js](cypress/integration/button-spec.js) | Clicks the button inside the iframe and checks the text
[single-its-spec.js](cypress/integration/single-its-spec.js) | Uses a single Cypress command to retry while iframe is loading
[custom-command-spec.js](cypress/integration/custom-command-spec.js) | Moves iframe access into a reusable common custom command
[spy-on-fetch-spec.js](cypress/integration/spy-on-fetch-spec.js) | Accesses `window` inside the iframe and spies on `fetch` calls
[xhr-spec.js](cypress/integration/xhr-spec.js) | Shows how to spy and stub network calls the iframe is making
