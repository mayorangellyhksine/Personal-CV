# Personal CV Website — Angel Lyhksine B. Mayor

A responsive personal CV and portfolio website for Angel Lyhksine B. Mayor, a fourth-year Bachelor of Science in Information Technology student at Davao del Norte State College.

## Live Website

Add your public Vercel URL here after deployment: `https://your-project-name.vercel.app`

## Technologies Used

- HTML5
- CSS3 (responsive layouts, gradients, transitions, and animations)
- JavaScript (mobile navigation, scroll reveal, active navigation)
- Git and GitHub
- Vercel

## Website Sections

- Personal profile and career objective
- About and basic information
- Technical skills
- Selected academic projects and concepts
- Education
- Experience and recognition placeholder
- Contact information and GitHub profile

## Projects Featured

1. **COTS Monitor** — Proposed Crown-of-Thorns Starfish detection and GIS mapping system.
2. **HomeFix Connect** — Home service provider platform concept.
3. **PhishShield+** — Phishing and scam detection concept.

Project status is described conservatively. The cards currently link to the owner's GitHub profile; replace those links with individual repository URLs when the projects are published.

## Run Locally

No build tools are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For local development, you can optionally use the Live Server extension in Visual Studio Code.

## Deploy to GitHub

1. Create a GitHub repository named `personal-cv`.
2. Open PowerShell in this project folder.
3. Run the following commands (replace the URL if your repository name differs):

```bash
git init
git add index.html style.css script.js README.md
git commit -m "chore: initialize personal CV website"
git branch -M main
git remote add origin https://github.com/mayorangellyhksine/personal-cv.git
git push -u origin main
```

If you already initialized Git or added a remote, do not repeat those commands blindly. Check with `git status` and `git remote -v` first.

## Deploy to Vercel

1. Sign in at https://vercel.com/ using GitHub.
2. Select **Add New → Project**.
3. Import the `personal-cv` repository.
4. As this is a static HTML/CSS/JS site, no framework or build command is needed. Leave the build command empty if Vercel allows it, and use `./` as the output directory if prompted.
5. Click **Deploy**.
6. Open the generated public URL and test all sections, links, and mobile layout.
7. Add the final URL to the Live Website section above and commit/push the README update.

## Suggested Meaningful Commit History

Make commits as you complete each step instead of making one commit for everything. Example:

```bash
git add index.html
git commit -m "feat: add CV sections and profile content"

git add style.css
git commit -m "style: add responsive light-pink portfolio design"

git add script.js
git commit -m "feat: add mobile navigation and scroll animations"

git add README.md
git commit -m "docs: add setup and deployment instructions"
```

Use these commands only for changes you actually made and have not already committed. Do not create fake commit history or backdate commits.

## Personal Details

- **Name:** Angel Lyhksine B. Mayor
- **Program:** Bachelor of Science in Information Technology
- **School:** Davao del Norte State College
- **Year level:** Fourth Year
- **Location:** Philippines
- **Email:** mayor.angellyhksine@dnsc.edu.ph
- **GitHub:** https://github.com/mayorangellyhksine

## Before Submission

- [ ] Replace or add a real profile photo if desired.
- [ ] Confirm that every project description matches its actual status.
- [ ] Update project links to specific public repositories when available.
- [ ] Add LinkedIn only after you have a profile URL.
- [ ] Add verified certificates, achievements, and experience if applicable.
- [ ] Test on desktop and mobile.
- [ ] Confirm the Vercel URL is publicly accessible.
- [ ] Submit both the Vercel link and GitHub repository link to the LMS.
