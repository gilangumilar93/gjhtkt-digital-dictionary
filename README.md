# The Digital Universe Dictionary

**Edition:** 1.0  
**Build date:** 2026-10-21  
**Glossary size:** 884 unique terms across 10 categories  
**Files:** `digital_universe_dictionary.html`, `digital_universe_dictionary.pdf`, `README.md`

## What this is

A practical, plain-English field guide to the digital world. Each entry contains:

- **Meaning:** a concise definition.
- **Context & use:** where the concept fits and when it matters.
- **Example:** a concrete, everyday technical or business scenario.
- **Related terms:** cross-references to nearby concepts.

The glossary covers AI foundations; prompting, RAG and AI agents; software engineering; web and networking; cybersecurity and reverse engineering; data and analytics; cloud and infrastructure; digital business and payments; operating systems, hardware and IoT; and emerging technology, privacy and digital society.

## Files

### HTML edition

Open `digital_universe_dictionary.html` in a modern browser. It is self-contained and designed to work offline after the file is saved locally.

Features:
- Full-text search across term, category, definition, context, examples and related terms.
- Category filters and topic navigation.
- Alphabetical, reverse-alphabetical and category sorting.
- Pagination for comfortable browsing.
- Browser-local bookmarks and bookmark export to JSON.
- Clickable related-term links.
- Source desk and monthly update log.
- Responsive layout and print-friendly CSS.

**Privacy note:** bookmarks are stored in the browser's local storage on the device where you open the file. They are not sent to a server. Use **Export bookmarks** to save a backup.

### PDF edition

`digital_universe_dictionary.pdf` is the print/read edition. It includes a short guide to using the glossary, a category contents list, source notes, and the entries grouped by category.

### README

This file documents the contents and update process.

## How to use it

1. Download all three files into the same folder.
2. Open the HTML file in Chrome, Edge, Firefox, or another modern browser.
3. Search an acronym or a plain-English phrase. For example: `RAG`, `reverse proxy`, `model routing`, or `least privilege`.
4. Use category filters to narrow the field.
5. Follow related terms to build a mental map rather than memorizing isolated definitions.
6. Use the PDF when you want to read offline, print, or annotate.

## Monthly update workflow

The glossary should be reviewed monthly because AI product names, APIs, protocols, standards, and security guidance can change.

1. **Check primary sources first.** Review official specifications, release notes, standards bodies, and vendor documentation. Do not use a social post as the sole authority for a technical definition.
2. **Look for material changes.** Prioritize new standards and protocols, newly common terms, deprecated names, significant product terminology changes, and security concepts that affect practice.
3. **Verify before adding.** Confirm the term's meaning, its use case, and one concrete example. Mark disputed or fast-changing definitions as context-dependent rather than pretending there is one universal definition.
4. **Edit the HTML dataset.** The glossary data is embedded in the HTML inside the element with `id="dictionary-data"` as JSON. Each record uses fields: `term`, `category`, `meaning`, `context`, `example`, `related`, and `id`.
5. **Maintain cross-references.** Ensure every related-term label exists in the dataset. Keep links useful and avoid circular lists of generic terms.
6. **Rebuild the PDF.** Regenerate the PDF from the same dataset so the HTML and PDF do not drift apart.
7. **Update the log.** Add a dated entry to the HTML's Monthly update log and this README. Increment the edition version for a meaningful monthly release.
8. **Verify the build.** Confirm term count, category count, search, category filters, bookmarks, related-term navigation, PDF page count, and that all three files open.
9. **Keep a changelog.** Record added terms, amended definitions, removals, and source links. Preserve prior versions if you need an audit trail.

### Suggested monthly review record

| Field | What to record |
|---|---|
| Review date | YYYY-MM-DD |
| Edition | e.g. 1.1 |
| Terms added | New verified entries |
| Terms updated | Definitions/examples changed and why |
| Terms retired | Deprecated or misleading terminology |
| Sources checked | Direct URLs to official sources |
| QA | Count, HTML interaction tests, PDF inspection |

## Recommended source desk

These sources are good starting points; consult the exact product or specification documentation for version-specific details.

- **NIST AI Risk Management Framework:** https://www.nist.gov/itl/ai-risk-management-framework
- **NIST Cybersecurity Framework:** https://www.nist.gov/cyberframework
- **MDN Web Docs:** https://developer.mozilla.org/
- **RFC Editor:** https://www.rfc-editor.org/
- **OWASP Top 10:** https://owasp.org/www-project-top-ten/
- **Model Context Protocol:** https://modelcontextprotocol.io/
- **Kubernetes concepts:** https://kubernetes.io/docs/concepts/
- **CISA:** https://www.cisa.gov/
- **W3C Web Accessibility Initiative:** https://www.w3.org/WAI/
- **PostgreSQL documentation:** https://www.postgresql.org/docs/
- **Python documentation:** https://docs.python.org/3/
- **C2PA:** https://www.c2pa.org/

## Editorial cautions

- This is a learning reference, not an exhaustive or authoritative standards dictionary.
- Some terms have multiple meanings. The category and example clarify the intended sense.
- Product features, API behavior, prices, model names, and plan limits change quickly; check official docs before making decisions.
- Security entries are educational. Test systems only when you own them or have explicit authorization.
- Legal, regulatory, medical, and financial applications require current domain-specific guidance.
- A model's explanation of its answer is not, by itself, proof that the answer is correct. Verify important claims against evidence.

## Build metadata

- Generated: 2026-10-21
- Unique glossary entries: 884
- Categories: 10
- HTML mode: self-contained/offline-first
- PDF mode: A4, printable, categorized entries
