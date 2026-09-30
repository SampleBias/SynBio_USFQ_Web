# HTBAA · USFQ Quito Node

Landing page for the Universidad San Francisco de Quito node of MIT HTBAA (How to Biomanufacture Almost Anything), a new course and a variant of HTGAA (How to Grow Almost Anything).

## Publish on GitHub Pages

GitHub Pages hosts this site for free from a public repository.

1. Create a public repository and push this folder to the `main` branch.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then save.
5. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`.

## A name like SynBio.USFQ

`SynBio.USFQ` is not a web address you can register. There is no public `.USFQ` domain ending. Two practical options:

- Ask USFQ for a subdomain on the university domain, such as `synbio.usfq.edu.ec`.
- Register a domain you control, such as `synbiousfq.org`.

When you have the hostname:

1. Add a file named `CNAME` in this folder containing only that hostname, for example `synbio.usfq.edu.ec`, and push it.
2. In **Settings → Pages**, enter the same hostname under **Custom domain**.
3. At the domain’s DNS host, point the name at GitHub:
   - For a subdomain (`synbio.usfq.edu.ec`), add a **CNAME** record aimed at `YOUR-USERNAME.github.io`.
   - For a root domain (`synbiousfq.org`), add the four **A** records GitHub shows in the Pages settings: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`.
4. Wait for DNS, then turn on **Enforce HTTPS** in the Pages settings.
