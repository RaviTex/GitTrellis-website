# GitTrellis website

The static site for [GitTrellis](https://gittrellis.vercel.app/). The desktop client, issue tracker and Fedora releases are in the [application repository](https://github.com/RaviTex/GitTrellis).

Serve the site locally with:

```sh
python3 -m http.server --directory public
```

Open [localhost:8000](http://localhost:8000). Vercel deploys the contents of `public/` on pushes to `main` in this repository. Open a pull request here to preview a website change. Pushes to the desktop repository run that repository’s CI and release workflow.

The application artwork and screenshots come from the GitTrellis application repository. See [LICENSE](LICENSE).
