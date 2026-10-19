# homeup-site

The landing page for HomeUp, served via GitHub Pages.

This is a build output. The source is the landing page in the HomeUp app (`apps/web/src/components/landing`). To update it, run this in the HomeUp repo and copy `apps/web/landing-static/dist/` here:

```bash
npm run build:landing-static -w apps/web
```

Set `VITE_SIGN_IN_URL` to the hosted app's `/login` page to show the Sign in buttons.
