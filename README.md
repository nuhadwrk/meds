# Medicine Lookup — public app only

This package contains the app, icons and offline support. It contains no book excerpts or bundled medicine database. Import your separately supplied private data file on your own device.

## GitHub Pages

1. Unzip `Medicine Lookup - PUBLIC GitHub.zip` and upload only its contents to your repository root. Do not upload the ZIP itself.
2. Settings → Pages → Deploy from a branch → main → /(root) → Save (choose your actual default branch if different).
3. Open the published HTTPS link in Safari.

No build or backend is required. Relative URLs work under a repository subpath.

## iPhone

1. Open the website online in Safari. Share → Add to Home Screen → Add; enable Open as Web App if shown.
2. Launch the Home Screen icon and wait for “Saved for offline use”.
3. Save `Medicine Data - KEEP PRIVATE.json` to your iPhone Files using AirDrop or your private file storage. Do not put this file in GitHub.
4. Inside the Home Screen app choose that JSON file under “Your private reference”. Wait for “Saved on this device”.
5. Close the app, enable Airplane Mode, and reopen. Test a medicine search.

Import inside the installed app: Safari and Home Screen apps may use separate storage. Keep a backup; iOS or clearing website data can remove local storage.

## Privacy and sources

Imports are parsed locally and saved in IndexedDB for this browser and site. No upload endpoint, analytics or external scripts are used. Your selected original PDF is opened locally and is not persisted; select it again after reopening. Offline caching contains only the app files. Imported reference data is stored separately on the device.

The data is not encrypted by the app. Anyone with access to this browser profile may view it. Hosting controls the app code: only use a host/repository you trust, and avoid other untrusted apps on the same web origin.

“Remove saved data” removes the imported reference from this browser, not your backup file. Failed imports leave the existing reference intact.

This independent tool is not affiliated with BNF publishers or NICE. Imported medical excerpts may be incomplete, old or incorrectly extracted; verify the full source and current guidance. The app supplies no license for imported material.

## Previous embedded-data versions

Replace the entire previously deployed site with this package; do not leave an old HTML file, entries.json, a PDF or data ZIP on the server. A file deleted from GitHub can still exist in repository history or prior copies. This package does not remove those copies. Nothing has been published automatically.
