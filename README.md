# helloworld-static-web

A sample Hello World static web page, hosted on **Azure Static Web Apps** (Free tier).

- Site content lives in [`src/`](src/).
- Every push to `main` deploys automatically via the GitHub Actions workflow in
  `.github/workflows/`.
- Pull requests get their own temporary preview environment.

To change the page, edit `src/index.html` and push to `main`.
