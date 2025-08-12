<!--
  README for: Michigan Cannabis Compliance — Source Library
  Notes:
  - Replace OWNER/REPO with your GitHub path to enable dynamic badges.
  - Static badges are included so this looks good even without changes.
-->

<!-- Title -->
<h1 align="center">Michigan Cannabis Compliance — Source Library</h1>
<p align="center">
  Versioned Michigan cannabis laws, administrative rules, and authoritative CRA publications.<br/>
  Built for stable citations, audit readiness, and AEO-friendly linking.
</p>

<!-- Badges (choose dynamic or static). Dynamic requires you to replace OWNER/REPO. -->
<p align="center">

  <!-- Dynamic badges (GitHub-powered): replace OWNER/REPO -->
  <a href="https://github.com/OWNER/REPO" title="Last commit on GitHub (dynamic)">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/OWNER/REPO?logo=github" />
  </a>
  <a href="https://github.com/OWNER/REPO" title="Repository size (dynamic)">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/OWNER/REPO?logo=github" />
  </a>
  <a href="LICENSE" title="Repository Notice">
    <img alt="License / Notice" src="https://img.shields.io/badge/License-Repository%20Notice-informational" />
  </a>

  <!-- Static badges (always correct; no OWNER/REPO needed) -->
  <img alt="Maintenance status" src="https://img.shields.io/badge/Status-Active%20maintenance-brightgreen" />
  <img alt="Last updated" src="https://img.shields.io/badge/Updated-Aug%2012%2C%202025-blue" />
  <img alt="Docs types" src="https://img.shields.io/badge/Docs-HTML%20%2B%20PDF-lightgrey" />
</p>

<hr/>

<!-- Link Grid -->
<h3 id="quick-links" aria-label="Quick links to laws, rules, and CRA documents">Quick Links</h3>

<table role="table" aria-label="Document navigation grid">
  <tr>
    <td valign="top" width="50%">
      <h4 id="laws-latest" aria-label="Laws (HTML latest)">🔹 Laws (HTML “latest”)</h4>
      <ul>
        <li><a href="laws/mrtma/latest/index.html" title="MRTMA — Initiated Law 1 of 2018 (HTML latest)">MRTMA — Initiated Law 1 of 2018</a></li>
        <li><a href="laws/mmfla/latest/index.html" title="MMFLA — Medical Marihuana Facilities Licensing Act (HTML latest)">MMFLA — Medical Marihuana Facilities Licensing Act</a></li>
        <li><a href="laws/mmma/latest/index.html" title="MMMA — Michigan Medical Marihuana Act (HTML latest)">MMMA — Michigan Medical Marihuana Act</a></li>
        <li><a href="laws/tracking-act/latest/index.html" title="Marihuana Tracking Act (HTML latest)">Marihuana Tracking Act</a></li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h4 id="admin-rules" aria-label="Administrative rules">🔹 Administrative Rules</h4>
      <ul>
        <li><a href="rules/latest/index.html" title="Consolidated administrative rules (HTML latest)">Consolidated HTML (latest)</a></li>
        <li><a href="rules/Marihuana_Administrative_Rules-R-4201-to-R-4201004-(OCR).pdf" title="Official PDF of administrative rules (OCR)">Official PDF (OCR)</a></li>
      </ul>
      <h4 id="cra-docs" aria-label="Authoritative CRA documents">🔹 CRA Documents (PDF)</h4>
      <ul>
        <li><a href="authoritative-documents/CRA_AFS_Report_FY25_Instruction_Booklet.pdf" title="AFS Report FY25 Instruction Booklet (PDF)">AFS Report FY25 Instruction Booklet</a></li>
        <li><a href="authoritative-documents/CRA_Compliance-Best-Practices-(2025-07).pdf" title="CRA Compliance Best Practices (July 2025, PDF)">Compliance Best Practices (2025-07)</a></li>
        <li><a href="authoritative-documents/CRA_Updated_Disciplinary_Guidelines_8624aag-(2025-07).pdf" title="CRA Updated Disciplinary Guidelines (July 2025, PDF)">Updated Disciplinary Guidelines (2025-07)</a></li>
        <li><a href="authoritative-documents/CRA_Tips_for_Licensees-Accounting_and_Recordkeeping_Best_Practices-(2025-04-24).pdf" title="CRA Tips for Licensees – Accounting & Recordkeeping Best Practices (April 24, 2025, PDF)">Tips for Licensees — Accounting & Recordkeeping (2025-04-24)</a></li>
        <li><a href="authoritative-documents/CRA_Multi-PacksTechnicalBulletin_Approved-(2025-04-09).pdf" title="CRA Multi-Packs Technical Bulletin (April 9, 2025, PDF)">Multi-Packs Technical Bulletin (2025-04-09)</a></li>
        <li><a href="authoritative-documents/METRC_MI_IB_95-Upload-Tolling-Agreements-(2025-01-21).pdf" title="Metrc MI IB 95 — Upload Tolling Agreements (Jan 21, 2025, PDF)">Metrc MI IB 95 — Upload Tolling Agreements (2025-01-21)</a></li>
      </ul>
    </td>
  </tr>
</table>

<hr/>

<!-- Extended Description -->
<h3 id="about" aria-label="What this is and why it exists">What this is &amp; why it exists</h3>
<p>
Most state links change when documents are updated, breaking citations in SOPs, articles, and audits. 
This repo hosts curated, dated copies and clean HTML so you can cite a stable path today and still find the exact text later.
</p>
<ul>
  <li><b>Link stability:</b> predictable relative paths that survive forks/renames.</li>
  <li><b>Historical archiving:</b> keep prior versions alongside <code>/latest/</code>.</li>
  <li><b>Direct HTML access:</b> statutes &amp; rules readable without downloading PDFs.</li>
  <li><b>Audit readiness:</b> cite what applied on a given date.</li>
</ul>

<!-- Usage -->
<h3 id="usage" aria-label="How to use this repository">How to use</h3>
<ul>
  <li>Need the current text? Link to the <code>/latest/</code> HTML (e.g., <code>laws/mrtma/latest/index.html</code>).</li>
  <li>Need an immutable citation? Link to a dated folder when available (e.g., <code>laws/mrtma/2025-07/index.html</code>).</li>
  <li>Need official artifacts? Use PDFs in <code>authoritative-documents/</code>.</li>
</ul>

<!-- Collapsibles keep the page tidy on GitHub -->
<details>
  <summary><b>Repo layout</b></summary>

<pre>
/
├─ authoritative-documents/
│  ├─ CRA_AFS_Report_FY25_Instruction_Booklet.pdf
│  ├─ CRA_Compliance-Best-Practices-(2025-07).pdf
│  ├─ CRA_Multi-PacksTechnicalBulletin_Approved-(2025-04-09).pdf
│  ├─ CRA_Tips_for_Licensees-Accounting_and_Recordkeeping_Best_Practices-(2025-04-24).pdf
│  ├─ CRA_Updated_Disciplinary_Guidelines_8624aag-(2025-07).pdf
│  └─ METRC_MI_IB_95-Upload-Tolling-Agreements-(2025-01-21).pdf
├─ laws/
│  ├─ mrtma/latest/index.html
│  ├─ mmfla/latest/index.html
│  ├─ mmma/latest/index.html
│  └─ tracking-act/latest/index.html
└─ rules/
   ├─ latest/index.html
   └─ Marihuana_Administrative_Rules-R-4201-to-R-4201004-(OCR).pdf
</pre>
</details>

<details>
  <summary><b>Citation format (suggested)</b></summary>
<p>
<i>Act/Rule/Doc title</i> §/R <i>section</i> (ed. <i>YYYY-MM</i>), <b>Michigan Cannabis Compliance — Source Library</b>, link to the specific file.
</p>
<p>Example: “MRTMA §8 (ed. 2025-07), Michigan Cannabis Compliance — Source Library, <code>laws/mrtma/2025-07/index.html</code>.”</p>
</details>

<details>
  <summary><b>Contributing</b></summary>
<ul>
  <li>PRs welcome for new official releases, HTML cleanup (headings/anchors only), and additional CRA bulletins.</li>
  <li>Keep filenames readable and dated: <code>Title-(YYYY-MM[-DD]).pdf</code>.</li>
  <li>No substantive edits to legal text.</li>
</ul>
</details>

<details>
  <summary><b>License &amp; attribution</b></summary>
<ul>
  <li>Original laws/rules are public domain/government works.</li>
  <li>HTML formatting &amp; curation © James Campbell, LLC (NUMBERS Accounting).</li>
  <li>Please attribute this repository when reusing the HTML or curated PDFs.</li>
</ul>
</details>

<!-- What's New / Changelog -->
<h3 id="changelog" aria-label="Changelog of important repository updates">What’s New</h3>

<ul>
  <li>
    <b>2025-08-12</b> — Major repo reorg; refreshed <code>README.md</code> with badges, link grid, collapsibles; confirmed
    paths for <code>laws/*/latest/</code> and <code>rules/latest/</code>.
  </li>
  <li>
    <b>2025-08-08</b> — Added CRA guidance set:
    <ul>
      <li>Metrc MI IB 95 — Upload Tolling Agreements (2025-01-21)</li>
      <li>Tips for Licensees — Accounting &amp; Recordkeeping (2025-04-24)</li>
      <li>Multi-Packs Technical Bulletin (2025-04-09)</li>
      <li>Compliance Best Practices (2025-07)</li>
      <li>Updated Disciplinary Guidelines (2025-07)</li>
      <li>AFS Report FY25 Instruction Booklet</li>
    </ul>
  </li>
  <li>
    <b>2025-08-05</b> — Confirmed HTML “latest” for MRTMA, MMFLA, MMMA, and Marihuana Tracking Act; added OCR’d Admin Rules PDF.
  </li>
</ul>

<!-- SEO helpers: add descriptive titles to key links above, keep headings semantic, and
     include domain language (Michigan, CRA, administrative rules, MRTMA, MMFLA, MMMA, METRC).
     GitHub ignores custom <meta> tags, so we use accessible titles/labels for discoverability. -->

