<div align="center">

<h1>Generative Advertisement Creation Pipeline</h1>

<img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=800&size=22&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=800&lines=Automated+Ad+Copy+%26+Visual+Compositions;Multi-Platform+Aspect+Ratio+Adaptation;Full-Stack+Creative+Automation+Studio;FastAPI+Backend+%2B+React+UI" alt="Typing Header" />

<p><strong>Generative System for Automated Ad Copywriting, Visual Synthesis, and Format Adaptation</strong></p>

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=python,fastapi,react,vite,ts,tailwind,github&theme=dark" alt="Skills" /></a>
</p>

</div>

---

## Executive Summary

AI Ads Maker is an automated marketing generation platform that transforms basic product inputs into structured, multi-channel advertising creatives. By coupling high-converting marketing copywriting templates with generative asset synthesis, the application generates targeted copy variants, product visuals, and formatted layouts across major advertising channels.

---

## Creative Studio Interface & Ad Output Gallery

<table align="center">
  <tr>
    <td align="center"><b>Campaign Ingestion Studio</b><br><sub>Product description, audience targeting, and tone configuration.</sub></td>
    <td align="center"><b>Generative Copy & Visual Matrix</b><br><sub>Dynamic headline variants paired with synthesized product layouts.</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="frontend/screenshots/1.jpg" alt="Campaign Studio" width="460"/></td>
    <td align="center"><img src="frontend/screenshots/2.jpg" alt="Ad Variants" width="460"/></td>
  </tr>
  <tr>
    <td align="center"><b>Multi-Platform Preview Canvas</b><br><sub>Visual inspection of 1:1, 9:16, and 16:9 responsive ad formats.</sub></td>
    <td align="center"><b>Asset Export & Production Package</b><br><sub>One-click batch asset export ready for ad platform deployment.</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="frontend/screenshots/3.jpg" alt="Preview Canvas" width="460"/></td>
    <td align="center"><img src="frontend/screenshots/4.jpg" alt="Export Package" width="460"/></td>
  </tr>
</table>

---

## System Architecture

```mermaid
flowchart TD
    A[Product Specifications & Brand Guidelines] --> B[Copywriting Formulation Engine]
    B --> C[Audience-Segmented Headlines & Value Propositions]
    A --> D[Visual Scene Prompt Generator]
    D --> E[Generative Asset Synthesis Service]
    C --> F[Canvas Composition & Typography Engine]
    E --> F
    F --> G[Multi-Ratio Layout Adapter: 1:1, 9:16, 16:9]
    G --> H[Final Ad Creative Package & High-Res PNG/MP4 Export]
```

---

## Technology Stack

| Layer | Technologies |
| :--- | :--- |
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| Backend Server | FastAPI, Python 3.10+, Uvicorn |
| Image Processing | Pillow, OpenCV |
| APIs | RESTful JSON Endpoints |

---

## Installation & Setup

```bash
# Clone the repository
git clone https://github.com/sohailahmed-bsrh/ai-ads-maker.git
cd ai-ads-maker

# Start backend
cd backend
pip install -r requirements.txt
python main.py

# Start frontend
cd ../frontend
npm install
npm run dev
```

---

## Author & License

- **Author**: Sohail Ahmed ([Portfolio](https://sohail.devsil.com) | [GitHub](https://github.com/sohailahmed-bsrh))
- **License**: Distributed under the MIT License.
