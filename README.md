# Company Research Card Kit

A free, static GitHub Pages resource for U.S. military personnel preparing to enter the civilian workforce. Students copy an evidence-based research prompt, open ChatGPT, enter a company name, and generate their own Company Research Card. There is no AI API or paid backend attached to this site.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `company-research-card-kit`, initialized with a README.
2. Clone with GitHub Desktop into `C:\GitHub\company-research-card-kit`.
3. Copy **the contents of this kit** into the repository root (replace the starter README). `index.html` must be at the top level.
4. Commit changes and **Push origin**.
5. In the repository on GitHub, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select `main`, folder `/(root)`, then **Save**.
7. Use **Visit site** once deployment completes and check the buttons and image.
8. The default site URL is `https://GITHUB-USERNAME.github.io/company-research-card-kit/`, substituting the real username. Make a QR code from the actual tested URL, not a guessed one.

This is a public website. Do not commit private files or credentials.

## Package contents

- `index.html`: student site, self-contained design and copy-prompt interaction
- `company-research-master-prompt.txt`: controlled student master prompt; text used by the website
- `assets/anduril-example.png`: AI-generated visual design reference **only**, not verified company imagery or factual evidence
- `.nojekyll`: publish static site without Jekyll processing

## Update the master prompt

The current prompt is embedded into `index.html` for reliable one-click copy from a GitHub Pages website. If you change `company-research-master-prompt.txt`, update the matching text embedded in `index.html` as well, or use a build script to regenerate it. Keep both in sync.

## Content and limitations

- Students access ChatGPT on their own accounts. Free plan usage limits and availability of image creation/file exports apply.
- Students must independently inspect sources and review any image output for factual correctness.
- This website does **not** run AI research. It distributes the instructions for students to use with ChatGPT.
- GitHub Pages is free for public repositories on GitHub Free, subject to GitHub's usage terms. It is not intended as free hosting for commercial SaaS.
- `assets/anduril-example.png` is generated, illustrative artwork and is not official Anduril media. It must not be represented as authoritative.

## Reference

Official publication instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
