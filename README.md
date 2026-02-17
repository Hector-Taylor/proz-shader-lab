# PROZ Shader Lab

Standalone shader experimentation app for live tuning and exporting GLSL / JSON presets.

## Local run

Open `index.html` directly, or run a static server:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Publish to GitHub (new repo)

1. Create a new empty GitHub repository (for example: `proz-shader-lab`).
2. In this folder, run:

```bash
cd /Users/hector/projects/Hector-Taylor.github.io/proz-shader-lab
git remote add origin git@github.com:<your-user>/proz-shader-lab.git
git branch -M main
git push -u origin main
```

If you prefer HTTPS:

```bash
git remote add origin https://github.com/<your-user>/proz-shader-lab.git
```

## Deploy to Vercel (Free / Hobby)

1. Go to https://vercel.com/new and import the GitHub repo.
2. Project settings:
   - Framework Preset: `Other`
   - Build Command: empty (no build)
   - Output Directory: `.`
3. Deploy.
4. Share the generated `*.vercel.app` URL.
