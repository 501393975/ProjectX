# Project X website

This is a static website for GitHub Pages. It needs no build step, framework, or API key.

## Publish with GitHub Pages

1. Push the project to a GitHub repository, including this `docs/` folder.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the default branch and the `/docs` folder, then save.
5. Wait for the Pages deployment to finish. GitHub shows the live address on that same settings page.

The APK download is `docs/downloads/projectxofficial890.apk`. Keep that file in the repository so the website download button continues to work. A custom domain can be configured later in the Pages settings.

To publish `app-ads.txt` from a custom domain, use that domain as the site's Pages custom domain and publish the file at the domain root. The root copy in this project contains the publisher line supplied by the app owner; AdMob still needs the site/domain to be entered in the Play listing and crawled.

The release APK uses the project's upload key. Keep `my-upload-key.jks` and its passwords backed up securely and never upload the keystore to a public repository.
