# Tushig Works

A quiet, one-page personal homepage for https://tushigworks.com.

## Publish on GitHub Pages

1. Create a public GitHub repository named `tushigworks`.
2. Upload `index.html`, `styles.css`, `landscape.svg`, and `CNAME` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, `main`, `/ (root)`.
4. In **Settings → Pages → Custom domain**, enter `tushigworks.com`.
5. In Spaceship DNS, add apex `A` records pointing to GitHub Pages IP addresses: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. For `www`, add a CNAME to `battushig-namsraidorj.github.io` if you want `www` to work.
6. Once GitHub verifies the DNS and provisions a certificate, enable **Enforce HTTPS**.

DNS may take time to propagate. Confirm current GitHub Pages DNS instructions before editing your DNS records.

No build tooling or JavaScript is required. Open `index.html` locally to preview.
