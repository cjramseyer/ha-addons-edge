# Changelog since v0.1.3
- Merge pull request #14 from cjramseyer/dev

Fix stale UI asset caching and add license token format options 
- Merge pull request #13 from cjramseyer/fix/license-delivery-cache-and-formats

Fix stale UI asset caching and add license token format options 
- Apply prettier formatting 
- Prevent stale UI asset caching and add license token format options

- Serve static assets with Cache-Control: no-cache so updated app.js/styles.css/index.html are always revalidated instead of served stale from browser/ingress cache.
- Add JWT / Base64URL / JSON Payload format switcher to the license Deliver modal, with matching Copy/Download behavior. 
