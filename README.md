# Xentrolance Technical Labs — GitHub Organization Profile

This project powers the **organization profile** and default community health files for **Xentrolance Technical Labs** on GitHub.

When published as a **public** repository named **`.github`** under your organization, [`profile/README.md`](./profile/README.md) appears on the org home page.

## What's Included

```text
.
├── profile/
│   ├── README.md                 ← Org profile (shown on GitHub)
│   └── assets/
│       ├── banner.svg            ← Hero banner
│       ├── typing.svg            ← Animated tagline
│       ├── focus.svg             ← Domain cards
│       ├── divider.svg           ← Section divider
│       ├── logo.svg              ← Brand mark
│       └── xentrolance-avatar.png← Suggested org avatar
├── assets/                       ← Source copies of visuals
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── SUPPORT.md
└── README.md
```

## Deploy (one-time)

### 1. Create the special repo

In your GitHub organization:

1. New repository named exactly **`.github`**
2. Visibility: **Public**
3. Skip initializing with a README if you will push this folder

### 2. Push this project

```powershell
git init
git add .
git commit -m "Add Xentrolance Technical Labs organization profile"
git branch -M main
git remote add origin https://github.com/<YOUR-ORG-SLUG>/.github.git
git push -u origin main
```

Replace `<YOUR-ORG-SLUG>` with your exact organization username.

### 3. Polish the org settings

In **Organization settings → Profile**:

- Upload `profile/assets/xentrolance-avatar.png` (or `logo.svg` exported to PNG) as the org avatar
- Set website to `https://xentrolance.com/`
- Add LinkedIn / social links if available

### 4. Verify

Open `https://github.com/<YOUR-ORG-SLUG>` — you should see the custom profile.

## Customize Later

- Swap contact email if `hello@xentrolance.com` is not the public inbox
- Link real public repositories under **Featured Workstreams**
- Add repo cards once you publish labs / open-source tools

---

**Xentrolance Technical Labs** — Engineering secure, intelligent systems for the enterprise.  
[xentrolance.com](https://xentrolance.com/)
