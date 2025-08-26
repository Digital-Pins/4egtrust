Maintenance GitHub Pages repo for 4egtrust.com

How to use:

1. Create a new repository on GitHub named `maintenance-4egtrust` (or any name) under the organization/account that owns `4egtrust.com`.
2. Push the contents of this folder to that repo's `main` branch, then enable Pages (the workflow will publish automatically):

   git init
   git add .
   git commit -m "Add maintenance page"
   git branch -M main
   git remote add origin git@github.com:YOUR_ACCOUNT/maintenance-4egtrust.git
   git push -u origin main

3. Ensure the repository's Pages settings use the `gh-pages` or the automatic artifact deployment (Actions will handle it).

4. DNS: point the A/ALIAS records for `4egtrust.com` to GitHub Pages as documented by GitHub, or configure an apex CNAME using the provider's ALIAS/ANAME if available.

Note: If the domain is already in use by another repo, remove previous CNAME or update DNS accordingly.
