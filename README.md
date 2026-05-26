# Wandernest Stays — Owner Portal

Live at: https://owners.wanderneststays.com.au

## What's in here

```
/index.html              → Main portal landing page
/guidebook/index.html    → Guest guidebook request form
/forms/onboarding.html   → Master onboarding template (blank)
/forms/properties/       → Pre-filled forms per property
  └── dales.html         → Dale's — 1/16 Wheatcroft St Scarborough
  └── amandas.html       → Amanda's — 7 Corinna St Falcon
  └── stuarts.html       → Stuart's — 102 Murray Waters Mandurah
```

## How to add a new property

1. Sarah voice-dumps property info to Claude
2. Claude generates a pre-filled HTML file
3. Save it to `/forms/properties/ownername.html`
4. Commit and push to GitHub
5. Send owner the link: `https://owners.wanderneststays.com.au/forms/properties/ownername.html`

## How to connect your custom domain

1. In GitHub Pages settings, set custom domain to `owners.wanderneststays.com.au`
2. In your domain registrar (where wanderneststays.com.au is registered), add a CNAME record:
   - Name: `owners`
   - Value: `yourgithubusername.github.io`
3. Done — takes 10-30 mins to go live

## Email notifications

All form submissions go to contact.sarahjaneproperty@gmail.com via formsubmit.co
