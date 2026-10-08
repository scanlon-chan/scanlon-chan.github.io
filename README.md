# Siyu Chen — Academic Website

An English academic portfolio focused on **Machine Learning for Real-World Sensing**, inspired by [PRISM](https://github.com/xyjoey/PRISM). The HTML, CSS, and JavaScript implementation is original; PRISM is referenced for its academic layout and typography. No build framework or package installation is needed.

## Content

- Visual learning: vertebral fracture cascades, VerteX-ID, transfer learning, and soft X-ray seed inspection.
- Signal representations: U-MFCC plant ultrasound.
- Interpretable prediction: DVT risk stratification.
- Engineering systems, education, academic service, patents, and software.
- Six research studies; four published papers and two manuscripts under review, as listed in the supplied CV.
- User-supplied portrait and scientific figures, Google Scholar, email, and uploaded PDF CV download.

Research facts come from the supplied CVs. The current public CV is the uploaded PDF, preserved byte-for-byte. The website mentor is Xiwen Bai only, as explicitly requested; the supplied PDF itself still lists Xiwen Bai and Yilin Wang. Tsinghua employment is shown as January 2025–March 2026. Patent application numbers are not represented as granted patents. Publication status should be updated as decisions arrive.

## Open and edit

Open `dist/index.html` directly. Deploy everything inside `dist/` for any static host. All paths are relative, so the site works at a domain root or GitHub repository path.

For text and study edits, edit `build_content.py` and run `python build_content.py`. The script writes `dist/index.html` and a research-data snapshot in `content/research.json`. It uses only the Python standard library. The optional `.openai/hosting.json` manifest is only used by ChatGPT Sites and is not required for GitHub Pages.

Edit `dist/styles.css` for appearance and `dist/script.js` for navigation and research filtering. Images live in `dist/assets/`; original scientific figures retain their content and aspect ratios, with transparent backgrounds flattened to white for readability.

## Publish with GitHub Pages

1. Create a public repository (recommended name: `scanlon-chan.github.io`).
2. Upload these project files, including `.github/workflows/pages.yml`.
3. In repository Settings → Pages → Build and deployment, choose **GitHub Actions**.
4. Push to `main`, or run the **Deploy academic website** workflow manually.
5. GitHub reports the live Pages URL in the workflow deployment result.

The workflow publishes only `dist/`. No secrets or access tokens are needed in the repository. The source CV and images are publicly downloadable when published.

## Journal impact factors

The two requested journals display 2025 Journal Impact Factors (released in 2026): Computers and Electronics in Agriculture, 10.3; IEEE Journal of Biomedical and Health Informatics, 7.7. Visible IF badges omit the metric year at the owner’s request. The source data retains the metric year for provenance. Article publication years remain visible. Values and source links are recorded in `content/journal-metrics.json` and defined in `build_content.py`. Sources were checked on 8 October 2026. Elsevier ScienceDirect confirms 10.3; BioxBio year tables confirm the 2025 metric year and both values, with the JBHI value also corroborated by GoingPub.

## Research stages

The 8 October 2026 update uses the supplied `Siyu Chen_CV(2).pdf` as the downloadable CV, unchanged. Research cards, publications, the experience timeline, and intellectual-property entries distinguish undergraduate work from RA work. Seed imaging is undergraduate research (August–December 2023); U-MFCC is continued research after graduation (July–December 2024), before the RA appointment. The RA appointment is January 2025–March 2026; DVT follow-up continued through April 2026. Publication years do not determine the research-stage grouping. The U-MFCC patent is grouped with its originating research, not with the RA appointment merely because it was published in 2025.
