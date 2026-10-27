<!-- Profile README for github.com/djsanti88-sudo/djsanti88-sudo -->
# Santiago Echeverri Gil

I build and quality-check AI training data: rubric-gated LLM pipelines, bilingual (EN/ES) review, and human-in-the-loop QA, shipped as real products.

## What I do

- **Rubric design** - turning "good output" into written, testable acceptance criteria that a model and a human reviewer can both apply.
- **LLM output evaluation** - scoring generated items against rubrics, tracking acceptance rates, and finding the failure modes behind rejections.
- **Bilingual EN/ES QA** - natural Latin American Spanish, with answer choices that align position by position with the English.
- **Human-in-the-loop review pipelines** - automated gates first, with the uncertain cases routed to a person.

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/djsanti88-sudo/sharpenly-showcase">
        <img src="https://raw.githubusercontent.com/djsanti88-sudo/sharpenly-showcase/main/docs/screenshots/social-preview.png" alt="Sharpenly" width="100%">
      </a>
      <h3><a href="https://github.com/djsanti88-sudo/sharpenly-showcase">Sharpenly</a></h3>
      <p>Bilingual EN/ES automotive training platform with a manager dashboard and hiring flow. About 20,300 bilingual questions from a rubric-gated LLM pipeline: acceptance raised from 14% to 84%, 10,356 of 11,870 generated items accepted, 451 routed to human review. 174 shipped versions.</p>
      <p><a href="https://app.sharpenlyapp.com">App</a> | <a href="https://sharpenlyapp.com">Site</a></p>
    </td>
    <td width="50%" valign="top">
      <!-- TODO: add a Scanbin screenshot (e.g. docs/screenshots/scanbin.png) and show it here with an <img> -->
      <h3><a href="https://github.com/djsanti88-sudo/smart-inventory-scanner">Scanbin</a></h3>
      <p>Barcode inventory scanner web app. A scan is cleaned, matched deterministically to a product, and counted instantly; unknown codes go through local catalogs first, then one capped LLM lookup, and anything unverified lands in a human Needs Review queue that teaches the system.</p>
      <p><a href="https://smart-inventory-scanner.vercel.app">Live demo</a></p>
    </td>
  </tr>
</table>

## Tools

Python, TypeScript, Next.js, Firebase, Playwright, RAG / Chroma, Claude API

## Contact

Santiago Echeverri Gil | djsanti88@gmail.com | [LinkedIn](https://www.linkedin.com/in/santiago-echeverri-gil/) | [sharpenlyapp.com](https://sharpenlyapp.com)
