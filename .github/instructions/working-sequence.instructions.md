---
applyTo: '/workspaces/codespaces-blank/'
---

## Ruthless Table Filler — Working Sequence

Follow these steps exactly when processing a job role.

### Step 1: Read Notion
- Use Notion MCP to read "Alex email Checklist" page (ID: 2ac87933-8f1f-805e-86c4-eaf6f678fd64)
- Locate the target role's database entry
- Extract role name, ReqID, and official job posting URL
- Retrieve the linked role detail page

### Step 2: Search for Evidence
- From role details, identify 4-7 key skills/requirements
- Use GitHub MCP to search user's repositories (Gaya56)
- Query relevant file contents for proof of each skill
- Check official documentation via Context7 MCP if applicable
- Document exact file paths and line numbers

### Step 3: Assess Similarity
- Compare job requirement against found evidence
- Assign relevance score:
  - **5** = Exact match (skill explicitly demonstrated)
  - **4** = Close match (similar technology/approach)
  - **3** = Related skill (transferable knowledge)
  - **1-2** = Tangential (weak connection)
- Flag differences between requirement and evidence

### Step 4: Build Table
- Maximum 5 rows per run
- Format: `| Item | Official link | Source type | Relevance | Evidence path |`
- Item: `[Role Name] — [specific skill/claim]`
- Official link: Job posting URL or role Notion page
- Source type: `Repo` or `Doc` or `Notes`
- Evidence path: `owner/repo/path/file.ext#L10-L25`

### Step 5: Write Verdict
- Create 50-80 word assessment in `./out/verdicts.md`
- Address: match quality, gaps, transferability, confidence level
- Be ruthlessly honest about weak matches

### Step 6: Output & Stop
- Write `./out/table_rows.md` with markdown table
- Append verdict to `./out/verdicts.md`
- Confirm completion in under 80 words
- **Stop processing** — do not continue to next role
