# OAuth public-site source review

These static pages describe the current personal YouTube OAuth workflow for the Google OAuth app. They contain no credentials, API keys, refresh tokens, or verification tokens. The pages are staged for GitHub Pages publication in the account-owned `tychen0927.github.io` user-site repository after checking that repository name is available.

The live site, if published, will be public at `https://tychen0927.github.io/`. Search Console ownership verification will use Google's generated HTML verification file and is separate from the credential grants.

No Google OAuth status change or token rotation is performed by these files. The OAuth scope is broad, app audience is External, and publication can let other Google Accounts request consent; this setup is intended for the owner's use only.
