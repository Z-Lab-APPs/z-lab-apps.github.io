# Z-Lab APPs · Support Pages

Support, privacy policy and terms pages for all of our apps, published with GitHub Pages at https://z-lab-apps.github.io/

## Structure

One folder per app. The folder name is the app's short slug:

```
index.html          # list of all apps (add a line for each new app)
<app-slug>/
  index.html        # support page (App Store "Support URL"), must show a contact email
  privacy.html      # privacy policy (App Store "Privacy Policy URL")
  terms.html        # terms of use
```

| App | Support URL | Privacy URL |
|---|---|---|
| BTT Singapore - Theory Test | https://z-lab-apps.github.io/bttsg/ | https://z-lab-apps.github.io/bttsg/privacy.html |

## Adding an app

1. Create `<app-slug>/` with the three pages above.
2. Add the app to the root `index.html` and to the table here.
3. Push to `main`; GitHub Pages redeploys automatically.

## app-ads.txt

`app-ads.txt` at the repo root is served at https://z-lab-apps.github.io/app-ads.txt (the domain root, as AdMob requires). It covers every app whose App Store "developer website" is https://z-lab-apps.github.io/. Keep one line per ad network account.
