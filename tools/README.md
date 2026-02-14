# Downloaded Tools

This directory contains tools that are downloaded from internal/private GitHub repositories.

## Tools

### autofind
- **Source Repository**: github/codeml-detector
- **Version**: v5.0.5
- **Download Command**: `gh release download "v5.0.5" -D ./tools --repo github/codeml-detector`

### ccrcli
- **Source Repository**: github/copilot-code-review-published-artifacts
- **Version**: v0.2.0
- **Download Command**: `gh release download "v0.2.0" -D ./tools --repo github/copilot-code-review-published-artifacts`

## Note

The current versions in this directory are placeholders because the actual tools are hosted in private GitHub repositories that require specific access permissions. 

To download the actual tools, use the GitHub Actions workflow:
```bash
gh workflow run download-tools.yml
```

Or run the download commands manually with appropriate GitHub authentication tokens that have access to the private repositories.
