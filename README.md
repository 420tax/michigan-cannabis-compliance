<!-- Title -->
<h1 align="center">Michigan Cannabis Compliance — Source Library</h1>
<p align="center">
  Versioned Michigan cannabis laws, administrative rules, and authoritative CRA publications.<br/>
  Built for stable citations, audit readiness, and AEO-friendly linking.
</p>

<hr/>

<!-- Link Grid -->
<h3>Quick Links</h3>

<table>
  <tr>
    <td>
      <h4>🔹 Laws (HTML “latest”)</h4>
      <ul>
        <li><a href="laws/mrtma/latest/index.html">MRTMA — Initiated Law 1 of 2018</a></li>
        <li><a href="laws/mmfla/latest/index.html">MMFLA — Medical Marihuana Facilities Licensing Act</a></li>
        <li><a href="laws/mmma/latest/index.html">MMMA — Michigan Medical Marihuana Act</a></li>
        <li><a href="laws/tracking-act/latest/index.html">Marihuana Tracking Act</a></li>
      </ul>
    </td>
    <td>
      <h4>🔹 Administrative Rules</h4>
      <ul>
        <li><a href="rules/latest/index.html">Consolidated HTML (latest)</a></li>
        <li><a href="rules/Marihuana_Administrative_Rules-R-4201-to-R-4201004-(OCR).pdf">Official PDF (OCR)</a></li>
      </ul>
      <h4>🔹 CRA Documents (PDF)</h4>
      <ul>
        <li><a href="authoritative-documents/CRA_AFS_Report_FY25_Instruction_Booklet.pdf">AFS Report FY25 Instruction Booklet</a></li>
        <li><a href="authoritative-documents/CRA_Compliance-Best-Practices-(2025-07).pdf">Compliance Best Practices (2025-07)</a></li>
        <li><a href="authoritative-documents/CRA_Updated_Disciplinary_Guidelines_8624aag-(2025-07).pdf">Updated Disciplinary Guidelines (2025-07)</a></li>
        <li><a href="authoritative-documents/CRA_Tips_for_Licensees-Accounting_and_Recordkeeping_Best_Practices-(2025-04-24).pdf">Tips for Licensees — Accounting & Recordkeeping (2025-04-24)</a></li>
        <li><a href="authoritative-documents/CRA_Multi-PacksTechnicalBulletin_Approved-(2025-04-09).pdf">Multi-Packs Technical Bulletin (2025-04-09)</a></li>
        <li><a href="authoritative-documents/METRC_MI_IB_95-Upload-Tolling-Agreements-(2025-01-21).pdf">Metrc MI IB 95 — Upload Tolling Agreements (2025-01-21)</a></li>
      </ul>
    </td>
  </tr>
</table>

<hr/>

<!-- Extended Description -->
<h3>What this is & why it exists</h3>
<p>
Most state links change when documents are updated, breaking citations in SOPs, articles, and audits. 
This repo hosts curated, dated copies and clean HTML so you can cite a stable path today and still find the exact text later.
</p>
<ul>
  <li><b>Link stability:</b> predictable relative paths that survive forks/renames.</li>
  <li><b>Historical archiving:</b> keep prior versions alongside <code>/latest/</code>.</li>
  <li><b>Direct HTML access:</b> statutes & rules readable without downloading PDFs.</li>
  <li><b>Audit readiness:</b> cite what applied on a given date.</li>
</ul>

<!-- Usage -->
<h3>How to use</h3>
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
  <summary><b>License & attribution</b></summary>
<ul>
  <li>Original laws/rules are public domain/government works.</li>
  <li>HTML formatting & curation © James Campbell, LLC (NUMBERS Accounting).</li>
  <li>Please attribute this repository when reusing the HTML or curated PDFs.</li>
</ul>
</details>
