# DengueWatch BD — privacy policy

The published privacy policy for the **DengueWatch BD** Android app, kept in its
own repository so its history and availability are independent of the app and of
the data pipeline.

Live at <https://druzzal.github.io/denguewatch-bd-privacy/>

That URL is referenced in two places, and both break if it moves:

1. The Google Play Console store listing — Play requires a reachable privacy
   policy URL for any app that requests location.
2. The app itself, in **About this data → Privacy → Read the privacy policy**
   (`FeedConfig.PRIVACY_POLICY_URL`).

## Publishing

GitHub Pages serves `index.html` from the `main` branch root. Enable it under
**Settings → Pages → Source: Deploy from a branch → main / (root)**.

## Editing

The policy describes what the app actually does, established by auditing the
code rather than from a template. If the app's behaviour changes — a new network
call, a new permission, anything stored differently — update this page, the
in-app copy, and the Play Data Safety answers together, and set a new effective
date.
