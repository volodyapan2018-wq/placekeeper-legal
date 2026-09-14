# PlaceKeeper support and legal pages

A standalone, dependency-free static website. No build step, JavaScript, external fonts, analytics, or external assets are required. Styling follows the device’s light/dark preference.

## Files

- `index.html`: support page
- `privacy.html`: Privacy Policy
- `terms.html`: Terms of Use, linking to Apple Standard EULA
- `styles.css`: shared responsive styling
- `README.md`: publishing instructions

## Preview locally

Open `index.html` in a browser. Links work directly from disk.

## Publish with GitHub Pages

1. Extract `placekeeper-legal.zip`.
2. Create a GitHub repository named `placekeeper-legal` (a public repository is the simplest option).
3. Upload the **contents** of the extracted `placekeeper-legal` folder to the repository root. `index.html` must be at the root, not inside a second folder.
4. Commit the files to the `main` branch.
5. Open the repository’s **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then save.
7. Wait for deployment to finish. GitHub Pages will display the published URL.

For a repository named `placekeeper-legal`, the URLs are typically:

- Support: `https://YOUR-USERNAME.github.io/placekeeper-legal/`
- Privacy: `https://YOUR-USERNAME.github.io/placekeeper-legal/privacy.html`
- Terms: `https://YOUR-USERNAME.github.io/placekeeper-legal/terms.html`

Replace `YOUR-USERNAME` with your actual GitHub username. Use the deployed URLs in App Store Connect and in your app wherever appropriate. Check all three pages after publishing. To update the site, edit the files and commit to `main` again.

## Content maintenance

Developer: Vladimir Panchenko  
Contact: volodyapan2018@gmail.com

The pages reflect the supplied app facts; no app source code was inspected. Keep them aligned with the shipping app and its SDK configuration, and update the displayed date when the policies change. Device backup behavior depends on device settings and app configuration. Hosting providers may process website request logs under their own policies.

References:

- Apple Standard EULA: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
- Apple privacy: https://www.apple.com/legal/privacy/
- Apple Maps privacy: https://www.apple.com/legal/privacy/data/en/apple-maps/
- RevenueCat privacy: https://www.revenuecat.com/privacy
- GitHub Pages documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

This package is separate from the application project. Publishing is not performed by creating the archive.
