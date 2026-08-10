# American Partners Community Development Foundation
## Coming Soon / Under Construction Page

This is the temporary landing page for **americanpartnersfoundation.org** while the full website is being built.

### Hosted via GitHub Pages

This single `index.html` file is deployed via GitHub Pages with a custom domain.

### To deploy:

1. Create a GitHub account at github.com (free)
2. Create a new **public** repository named `americanpartnersfoundation.org` (or any name)
3. Upload `index.html` and this `README.md`
4. Go to **Settings → Pages**
5. Under "Source," select **Deploy from a branch → main → / (root)**
6. Under "Custom domain," enter `americanpartnersfoundation.org` and click Save
7. At your domain registrar (Namecheap, GoDaddy, etc.), add these DNS records:

```
Type    Host    Value
A       @       185.199.108.153
A       @       185.199.109.153
A       @       185.199.110.153
A       @       185.199.111.153
CNAME   www     YOUR-GITHUB-USERNAME.github.io
```

8. Wait 10–30 minutes for DNS to propagate. GitHub will auto-provision HTTPS (free SSL).

### Before going live — replace these placeholders:

- `[XX-XXXXXXX]` → your real EIN
- `info@americanpartnersfoundation.org` → your real email once Google Workspace is active
- Status checklist items → update to reflect your actual progress
- Notify form → wire to Formspree (free) or Mailchimp for real email capture

### Swap in the full site:

When your full website (`index.html` from the complete site build) is ready, simply replace this file with it in the GitHub repository. No other changes needed — same domain, same hosting.
