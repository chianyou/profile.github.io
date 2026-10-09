# Chianyou Lin — Personal Portfolio

Personal portfolio website showcasing my work in data analytics, machine learning and computer vision.

🔗 **Live site:** <!-- replace with your GitHub Pages URL -->

## About me

MSc Business Analytics, University College London · BSc Data Science, Soochow University.

Experienced in data analytics, machine learning and computer vision. I have hands-on experience building predictive models, analytics dashboards and end-to-end ML pipelines.

## What's on the site

| Section | Content |
|---|---|
| **About** | Profile summary and focus areas |
| **Work Experience** | Timeline of roles, each with a project gallery (click to enlarge) |
| **Education** | UCL (MSc Business Analytics) and Soochow University (BSc Data Science) |
| **Projects** | Featured projects, certifications and GitHub repositories |
| **Contact** | Email, GitHub and LinkedIn |

### Work highlights

- **BatFast — Machine Learning Engineer** (Nottingham, UK · Apr 2026 – Sep 2026)
  Automated batter-readiness detection with PyTorch, YOLOv8 pose estimation and EfficientNet classifiers. Accuracy reached 93.4% for readiness and 98.1% for helmet detection.
- **Hua Nan Commercial Bank — Data Analyst Intern** (Taipei, Taiwan · Jul 2024 – Jul 2025)
  Built XGBoost predictive models, fraud detection work and Tableau BI dashboards. Took 2nd place in a company-wide BI Hackathon.

> Dashboard screenshots on the site use mock data for demonstration purposes only.

## Tech stack

- HTML5, CSS3, JavaScript
- Bootstrap 4 (responsive layout)
- jQuery
- GitHub REST API (repositories are loaded automatically)
- Hosted on GitHub Pages

## Project structure

```
myprofile/
├── index.html   # All page content, plus custom styles in the <style> blocks
├── css/         # Template stylesheets (Bootstrap, base theme)
├── js/          # Template scripts (jQuery, Bootstrap, plugins)
└── images/      # Photos, logos, project screenshots and demo videos
```

## Updating the site

- **Text and layout:** edit `myprofile/index.html`. The custom styles live in the `<style>` blocks inside this file, so `css/` rarely needs changes.
- **Images:** add them to `myprofile/images/`. To keep the site fast:
  - Resize photos to about 1200px wide or smaller, and save them as JPG.
  - Use MP4 instead of GIF for animations. The file is about 20× smaller.
- **GitHub repositories:** these update automatically. To change the text shown on a card, edit that repo's description on GitHub.
- **After uploading:** GitHub Pages takes 1–2 minutes to update. Press `Cmd + Shift + R` to bypass the browser cache.

## Local preview

```bash
cd myprofile
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Contact

- Email: chianyou.lin@gmail.com
- GitHub: [@chianyou](https://github.com/chianyou)
