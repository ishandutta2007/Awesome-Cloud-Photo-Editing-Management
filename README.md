# Awesome-Cloud-Photo-Editing-Management

# Top Cloud Photo Editing & Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Non-Destructive RAW Editing, Library Management & Self-Hosted Photography Workflows*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Photo Editing & Management**. These tools help photographers organize large image libraries, develop RAW files, and publish finished work—ranging from subscription-based cloud ecosystems to fully offline open-source pipelines that keep your photos entirely on your own hardware.

**Examples** include Adobe Lightroom, Capture One, DxO PhotoLab, ON1 Photo RAW, Skylum Luminar Neo, darktable, and RawTherapee (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription lock-in, and controlling the entire photography pipeline. The open-source landscape is anchored by **darktable** (the full Lightroom replacement with non-destructive scene-referred editing and a built-in catalog), **RawTherapee** (the RAW conversion engine for pixel-peepers), and **digiKam** (the library management specialist), with **ART** serving users who want RawTherapee's engine with a friendlier interface.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Adobe Lightroom](https://www.adobe.com/lightroom)** | Cloud-first photo editing and management with 1TB storage. | **1TB Plan**: **$14.99/month** (annual billed monthly) or **$149.99/year** prepaid (increased from $11.99/$119.88 in March 2026) . | **7-day free trial** available on the 1TB plan . No permanent free tier. |
| **[Capture One Pro](https://www.captureone.com/)** | Professional RAW editor with tethering and color grading tools. | **Subscription**: ~**¥63.08/month**; **Perpetual license**: ~**¥1,261.00** . Prices increased 6% across products in July 2026 . | **30-day free trial** available . No permanent free tier. |
| **[DxO PhotoLab 10](https://www.dxo.com/)** | One-time-purchase RAW editor with AI masking and optical corrections. | **$249.99** one-time (new license); **$129.99** upgrade from PhotoLab 8 or 9 . | **30-day free trial** available . No permanent free tier. |
| **[ON1 Photo RAW 2027](https://www.on1.com/)** | All-in-one editor available as perpetual or subscription. | **Perpetual**: **MX$1,947.30** (sale price, includes versions 2026 and 2027). **Subscription (MAX)**: MX$1,752.56/year . | No permanent free tier. Trial available via ON1. |
| **[Skylum Luminar Neo](https://skylum.com/)** | AI-focused editor with sky replacement, relighting, and generative tools. | **Perpetual Desktop License**: **HKD 788** (sale price, includes 1 year of upgrades). Cross-device and Max tiers available . | **7-day free trial** with full access . No permanent free tier. |
| **[Corel AfterShot Pro 3](https://store.aftershotpro.com/)** | Fast RAW editor with Linux support. | **HK$657.38** (sale price; regular HK$988.00) . | No free tier. Trial available. |

## Open-Source GitHub Projects

- **[darktable](https://github.com/darktable-org/darktable)** [![GitHub Stars](https://img.shields.io/github/stars/darktable-org/darktable?style=social&color=white)](https://github.com/darktable-org/darktable/stargazers)  
  **The full open-source Lightroom replacement.** GPL licensed. **Non-destructive editing** with a scene-referred pipeline that v5 rewrote to beat Lightroom for shadow rolloff on most raw sensors . **Library management**: built-in catalog handles large collections; parametric masking is unmatched in the free tier; tethered shooting supports Canon, Nikon, Sony, and Fuji . **Trade-offs**: steeper learning curve than Lightroom—module names borrow from image science, not photography; face recognition is not built in, and album views feel bolted on . Best for photographers wanting a complete, free pipeline where editing quality is the priority.

- **[RawTherapee](https://github.com/RawTherapee/RawTherapee)** [![GitHub Stars](https://img.shields.io/github/stars/RawTherapee/RawTherapee?style=social&color=white)](https://github.com/RawTherapee/RawTherapee/stargazers)  
  **The RAW conversion engine for pixel-peepers.** GPL licensed. Demosaicing options include AMaZE, RCD, and DCB; wavelet controls give more granular sharpening than anything else in the free tier . v5.10 improved multithreaded queue and cut export times . **Critical limitation**: **not a library tool**—edits one file at a time and expects an external browser for organization . Best paired with digiKam for cataloging; the classic free photographer's stack is "catalog in digiKam, edit in RawTherapee."

- **[digiKam](https://github.com/KDE/digikam)** [![GitHub Stars](https://img.shields.io/github/stars/KDE/digikam?style=social&color=white)](https://github.com/KDE/digikam/stargazers)  
  **The free catalog nobody talks about.** GPL licensed. The most serious attempt at Lightroom's library half—keeps a real database, handles hierarchical keywords, faces, geotagging, and metadata properly, and scales to large collections . **Interface shows its age** and editing tools are thin, but as a place to keep and find work, it has been quietly solving the problem for years . Best as the catalog layer in a free stack, calling darktable or RawTherapee as external editors.

- **[ART (Another RawTherapee)](https://github.com/artraweditor/ART)**  
  **RawTherapee's engine with a friendlier UI.** Fork of RawTherapee with simpler interface and better defaults for users who found the original intimidating . **Trade-offs**: smaller community, fewer tutorials, active single-maintainer development, and no catalog/library . Best for users who want RawTherapee's RAW quality without its density.

### Additional Strong Open-Source Options

- **GIMP** — Open-source raster editor for pixel-level retouching and compositing. Best for finishing touches beyond RAW development.
- **XnView MP** — Free image browser and converter. Best for quick browsing alongside RawTherapee when digiKam's catalog is overkill.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Open-source covers most of Lightroom's halves, not all**: darktable comes closest for the develop module; digiKam comes closest for the catalog—but **nothing free covers both halves to Lightroom's standard** . Expect to combine tools.
- **AI masking is the biggest gap**: Lightroom's AI subject/sky/background masking is excellent and **largely missing from open-source equivalents**—darktable has parametric and drawn masks, but not AI masks . If AI masking is core to your workflow, the free options cannot match.
- **Mobile sync is absent from open source**: darktable and RawTherapee have no mobile apps; Lightroom's desktop-to-mobile sync is a paid advantage that free tools do not replicate .
- **Subscription prices are rising**: Adobe's Lightroom 1TB plan increased to $14.99/month in March 2026 ; Capture One raised prices 6% in July 2026 . DxO and ON1 remain one-time-purchase alternatives with optional upgrades.

---

**Made for photographers, photo librarians, and anyone who wants control over their image pipeline without subscription lock-in.**  
Let's make cloud photo editing and management more open, non-destructive, and self-hostable.
