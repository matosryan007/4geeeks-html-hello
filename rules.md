## Title Tags: Your Clickable Headline

The title tag appears as the blue clickable headline in search results and as the browser tab name. It is the single most important on-page SEO element.

**Best practices:**
- Keep it between 50–60 characters to avoid truncation in search results.
- Front-load your most important keywords.
- Include your name or brand, usually at the end.
- Make it descriptive and specific — avoid vague labels like "Home" or "Page 1."

## Meta Descriptions: Your Sales Pitch

The meta description is the summary text below the title in search results. It does not directly affect your ranking, but it strongly influences whether someone clicks.

**Best practices:**
- Keep it around 150–160 characters.
- Summarize the page's value clearly.
- Include a call-to-action or specific detail that invites the reader in.
- Write for the human reader, not just the algorithm.

## Headings and On-Page Structure

The H1 matches the title tag, H2s divide the major sections, and H3s break down sub-topics within each section — a clear hierarchy that serves both users and search engines equally well.

**Best Practices:**
- Use one H1 tag per page — it should closely match your title tag for SEO consistency.
- Follow a sequential order: never skip heading levels (do not jump from H1 to H3 without an H2 in between).
- Use headings to structure content, not to control font size or visual style — control appearance with CSS.
- Make headings descriptive and meaningful so users can scan and understand the page at a glance.

SEO-optimized page combines the title tag, meta description, and a clean heading structure.

---

## Making Your Content GEO-Ready

Optimizing for AI search means making your content easy to understand, trustworthy, and conversational. Concretely:

- **Write conversational introductions.** Start each page with a clear, plain-language answer to the question "What is this page about?" Think of it as explaining the topic to a friend — avoid jargon or explain it when you use it.
- **Use question-based headings in FAQ sections.** AI extracts precise answers by matching your headings to user queries. An H2 named "Frequently Asked Questions" with H3 headings that are actual questions ("How do I center a div in CSS?") helps AI identify and cite your content accurately.
- **Add author information.** A brief footer with the author's name, role, and relevant experience signals expertise and trustworthiness. AI search tools value credibility when deciding what to cite.
- **Use structured data as the bridge.** Schema.org markup makes your content explicitly machine-readable — it labels what type of content each part of your page is, what entities are involved, and what facts are stated. It benefits both traditional SEO (enabling rich results in Google) and GEO (helping AI understand your content's meaning, not just its text).

---

## A Testing Workflow for Accessibility

A reliable audit runs these passes in order, from fastest to most thorough:

1. **Automated audit** — run Lighthouse or axe to surface obvious problems.
2. **Keyboard pass** — confirm everything is reachable and operable without a mouse.
3. **Screen reader pass** — verify announcements, labels, and error messages.
4. **Visual pass** — check contrast, focus indicators, and layout at different zoom levels.

As you go, ask the questions that matter most: does every image have meaningful alt text, can the whole site be used by keyboard, are form fields labeled and errors clear, is the tab order logical, and do focus indicators meet contrast requirements?