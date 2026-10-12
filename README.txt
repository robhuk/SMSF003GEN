XC Staff Report Writer PWA

Files are kept together in the app root:
- index.html
- manifest.json
- sw.js
- icon.svg

Deploy the contents of this folder to a static HTTPS host (for example GitHub Pages) to install it as a PWA. Offline caching is enabled after the first successful load. The app does not upload report data to a server. TXT download, clipboard copy, email draft, and browser Print / Save PDF are supported.

Reports are generated from the uploaded XC Report Writing Template. Check every report for accuracy and completeness before submission.


Installation identity: this release uses a distinct manifest ID (smsf003gen-report-writer-v2) to avoid Android Chrome treating it as the previously installed PWA. The manifest start URL and scope are relative to this folder, so deploy the folder contents together in the same location.
