---
agent: Table-filter-skills-To-Job-description
---

# Task: Combine All Job Evidence into Unified Report

## Objective
Consolidate all individual job evidence tables and verdicts from `/workspaces/codespaces-blank/out/` into a single comprehensive report.

## Source Directories
1. `/workspaces/codespaces-blank/out/GenAI-QA-Consultant-669776WD/`
2. `/workspaces/codespaces-blank/out/GenAI-Developer-Associate-673050WD/`
3. `/workspaces/codespaces-blank/out/UX-UI-GenAI-Developer-Senior-Associate-669127WD/`
4. `/workspaces/codespaces-blank/out/Project-Coordinator-678714WD/`

## Output Requirements
Create `/workspaces/codespaces-blank/out/COMBINED_EVIDENCE_REPORT.md` with:

#IMPORTANT#: Create a separate checklist of what don't have from the job description and evidence highlight them in red so that i can focus on them while applying for the job making sure i cover all the points mentioned in the job description while applying for the job.

1. **Executive Summary** (100-150 words)
   - Overview of 4 jobs processed
   - Total evidence rows (20)
   - Strongest matches identified
   - Overall portfolio assessment

2. **Evidence by Role** (for each job)
   - Role title and ReqID
   - Evidence table (all 5 rows)
   - Verdict (copied verbatim)
   - Match score summary

3. **Cross-Role Analysis**
   - Skills appearing across multiple roles
   - Strongest technical capabilities demonstrated
   - Notable gaps or missing evidence
   - Repos contributing most evidence

4. **Application Strategy**
   - Recommended prioritization (which roles to pursue)
   - Key talking points per role
   - Skill development recommendations

## Format
- Use proper markdown headers (##, ###)
- Keep tables properly formatted
- Include Notion links for each role
- Maintain professional, concise tone

---

**Begin processing now.**
