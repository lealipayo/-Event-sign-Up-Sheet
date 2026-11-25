# Commit 1: Add .gitignore
git add .gitignore
git commit -m "Add .gitignore to exclude environment and OS files"

# Commit 2: Add README.md with community problem and FR-01
git add README.md
git commit -m "Add README.md with community problem and FR-01"

# Commit 3: Add PROJECT_BRIEF.md
git add PROJECT_BRIEF.md
git commit -m "Add one-page project brief (PROJECT_BRIEF.md)"

# Commit 4: Add initial PROMPT_LOG.md
git add PROMPT_LOG.md
git commit -m "Add initial AI-use log in PROMPT_LOG.md"

# Commit 5: Add a version comment/update to index.html
echo "<!-- Verified v0.1.0 Campus Information & Alert Center -->" >> index.html
git add index.html
git commit -m "Add v0.1.0 verification header in index.html"

## 6 — Final End-to-End Verification & Release Preparation
- **Prompt:** Perform a final end-to-end verification of the deployed Medina College Ipil — Campus Information & Alert Center web app, checking FR-01 notice creation, pinning, filtering, alert resolution, and localStorage persistence.
- **Result:** Confirmed all interactive workflows and repository documentation for Release v0.1.0.
- **Verified:** Tested on Android browser and verified persistence across page reloads.
- **Commit:** Log final verification prompt in PROMPT_LOG.md
EOF
git add PROMPT_LOG.md
git commit -m "Log final verification prompt in PROMPT_LOG.md"

