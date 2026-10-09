# flydownwind.app – Downwind web version

GitHub Pages site with the **web version of the Downwind app** (for Android and the computer; same account and data as the iPhone app,
no automatic recording – flights are imported from an EFB app or entered by hand).

- Built from the app repo: `npm run publish:web` (in `downwind`), then commit + push this repo.
- `404.html` still forwards unknown paths to the same path on https://flydownwind.ch.
- Supabase → Authentication → URL Configuration must allow `https://flydownwind.app/**` as redirect URL (sign-in link).
- `.app` domains are HTTPS-only; GitHub Pages issues the certificate (Settings → Pages → Enforce HTTPS).
