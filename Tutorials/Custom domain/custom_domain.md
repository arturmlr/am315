# golinked.bio — Custom Domain Setup Guide

A step-by-step guide to connect a **custom domain** purchased on **GoDaddy** to your **golinked.bio** account using Cloudflare nameservers.

---

## Table of Contents
- [Step 1: Purchase a Domain (GoDaddy)](#step-1-purchase-a-domain-godaddy)
- [Step 2: Access DNS Management](#step-2-access-dns-management)
- [Step 3: Open Custom Domain Settings in golinked](#step-3-open-custom-domain-settings-in-golinked)
- [Step 4: Enter Your Domain](#step-4-enter-your-domain)
- [Step 5: Open GoDaddy Domain Settings](#step-5-open-godaddy-domain-settings)
- [Step 6: Update Nameservers with Cloudflare](#step-6-update-nameservers-with-cloudflare)
- [Step 7: Add Your Custom Domain in golinked](#step-7-add-your-custom-domain-in-golinked)
- [Step 8: Assign Your Custom Domain to a Link](#step-8-assign-your-custom-domain-to-a-link)
- [Step 9: Choose Custom Domain Options](#step-9-choose-custom-domain-options)

---

### Step 1: Purchase a Domain (GoDaddy)

- Search for your desired domain on GoDaddy.  
- Add it to your cart and complete the checkout process.  
- Once purchased, your domain will appear in your GoDaddy account under **My Products**.  

![Purchase domain](Assets/00_buy_domain.png)

---

### Step 2: Access DNS Management

- In your GoDaddy account, go to **My Products → Domains**.  
- Select your new domain and open **DNS Management**.  
- Keep the domain name copied — you’ll need it in the next steps.  

![Copy domain](01_copy_domain.png)

---

### Step 3: Open Custom Domain Settings in golinked

- Log in to your **golinked** profile.  
- Go to **Settings → Custom Domains**.  
- Click on **Add Domain**.  

![Add domain in golinked](02_add_domain.png)  
![golinked add domain screen](03_golinked_add_domain.png)

---

### Step 4: Enter Your Domain

- Paste your purchased domain into the input field.  
- Confirm to proceed.  

![Open GoDaddy domain settings](04_open_godaddy_domain_settings.png)

---

### Step 5: Open GoDaddy Domain Settings

- In golinked, scroll down to the **GoDaddy section**.  
- Click **Open GoDaddy Domain Settings** to adjust your DNS.  

![Change nameservers in golinked](05_golinked_change_nameservers.png)

---

### Step 6: Update Nameservers with Cloudflare

- Copy the **Cloudflare nameservers** shown in golinked.  
- In GoDaddy, go to **DNS → Nameservers → Change Nameservers**.  
- Select **I’ll use my own nameservers**.  
- Paste the Cloudflare nameservers.  
- Save and confirm.  

![Copy nameservers](06_copy_nameserver_golinked.png)  
![Edit nameservers](07_Edit_nameserver.png)  
![Paste nameservers](08_paste_nameserver.png)

---

### Step 7: Add Your Custom Domain in golinked

- Go back to golinked.  
- Click **Add Domain** again to verify and start propagation.  

![Add domain final step](09_add_domain_last_step.png)

---

### Step 8: Assign Your Custom Domain to a Link

- Once verified, open your golinked dashboard.  
- Go to your links and select your new **custom domain**.  

![Custom domain overview](10_custom_domain_overview.png)  
![Custom domain link settings](11_Custom_Domain_Link.png)

---

### Step 9: Choose Custom Domain Options

- You can choose between:  
  - Root Domain (`example.com`)  
  - Subdomain (`links.example.com`)  
  - Path (`example.com/username`)  

- Save the link to finish.  

![Choose custom domain link](12_choose_custom_domain_link.png)

---

## Propagation Time

- Domains usually activate within **10–20 minutes**.  
- In some cases, full DNS propagation can take up to **48 hours**.  

---

## Tips & Common Pitfalls

- **One registrar at a time**: After switching nameservers to Cloudflare, manage DNS only in Cloudflare.  
- **Check spelling**: Nameservers must be copied exactly.  
- **Propagation takes time**: Wait up to 48h before retrying.  
- **HTTPS/SSL**: Configured automatically by golinked once domain is active.  

---

## Support

If you run into issues, collect screenshots of your **GoDaddy Nameservers page** and **golinked Custom Domains settings** and contact golinked support.

