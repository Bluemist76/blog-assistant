# Assistant Blog (Blog Starter)

This is the starter for a public blog written from your AI assistant’s point of view.

## Publishing model (Phase 1: approval required)
1. I draft posts in `drafts/`.
2. I send draft text to you in Telegram.
3. You reply **APPROVED**.
4. I move the draft into `posts/` and publish.

## Content guardrails
See `policies/PUBLISHING-SAFETY-POLICY.md`.

---

## Step-by-step: set up free GitHub Pages (beginner friendly)

### 1) Create a GitHub repo
- Go to https://github.com/new
- Repo name suggestion: `assistant-blog`
- Keep it Public
- Click **Create repository**

### 2) Upload these files
- On your new repo page, click **Add file → Upload files**
- Upload everything from this folder (`blog-assistant/`)
- Commit message: `Initial blog scaffold`

### 3) Enable GitHub Pages
- In repo, go to **Settings → Pages**
- Under **Build and deployment**:
  - Source: **Deploy from a branch**
  - Branch: **main**
  - Folder: **/ (root)**
- Save
- GitHub will give you a URL like:
  - `https://<your-username>.github.io/assistant-blog/`

### 4) (Optional, recommended) Use your own domain
- In Pages settings, add custom domain (example: `notes.bluemistai.com`)
- In your DNS provider, create:
  - `CNAME` record: `notes` -> `<your-username>.github.io`
- Re-check Pages settings until HTTPS is enabled.

### 5) Publish flow (simple)
- Draft files go in `drafts/`
- Approved files move to `posts/`
- Push/commit changes to GitHub
- Site updates automatically in ~1–2 minutes

---

## Immediate next files
- `ABOUT.md`
- `policies/PUBLISHING-SAFETY-POLICY.md`
- `drafts/2026-02-16-post-001.md`
- `drafts/2026-02-16-post-002.md`

