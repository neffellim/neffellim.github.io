Personal rclone Google OAuth Branding — GitHub Pages starter

1) Replace YOUR_APP_NAME in index.html and privacy.html with the exact application name used in Google Auth Platform > Branding.
2) Replace YOUR_PUBLIC_CONTACT_EMAIL with an email address you are comfortable displaying on a public website. Match the support contact on Google's consent screen.
3) Create a PUBLIC GitHub repository named YOUR_GITHUB_USERNAME.github.io and put index.html and privacy.html in its root.
4) In GitHub repository Settings > Pages, deploy from branch main, folder /(root). Once published check:
   https://YOUR_GITHUB_USERNAME.github.io/
   https://YOUR_GITHUB_USERNAME.github.io/privacy.html
5) In Google Search Console create a URL-prefix property for https://YOUR_GITHUB_USERNAME.github.io/ and use the HTML-file verification method. Add the exact Google-provided verification file to the repository root, publish, then click Verify in Search Console.
6) In Google Auth Platform > Branding attempt to register your precise hosted domain as an Authorized domain, fill homepage and privacy-policy URLs, and save. GitHub Pages subdomains may not be accepted as OAuth Authorized Domains; do NOT treat Search Console verification alone as a guarantee. If rejected, use a domain you own, hosted on GitHub Pages if desired.
7) Google Auth Platform > Audience: click Publish app once required fields validate.
8) Reconnect existing rclone OAuth after publish, verify with rclone lsd gdrive:, then test a safe manual sync run.

No client IDs, client secrets, OAuth refresh tokens, user data, or internal documents belong in this public repository.

Review the page copy and privacy statements for accuracy against your actual configuration before publishing.
