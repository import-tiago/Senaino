# Citation And DOI

This repository is prepared for DOI-based citation through GitHub releases archived by Zenodo.

## Citation Metadata

The root [../CITATION.cff](../CITATION.cff) file provides machine-readable citation metadata for GitHub, Zotero and citation tooling.

The root [../.zenodo.json](../.zenodo.json) file provides Zenodo-specific metadata for release archiving.

## Recommended Release Tag

Use this tag for the FT232 release:

```text
ft232-v1.0.0
```

Suggested GitHub release title:

```text
Senaino FT232 v1.0.0
```

## DOI Workflow

1. Enable the GitHub repository in Zenodo.
2. Create a GitHub release from the `ft232-v1.0.0` tag.
3. Wait for Zenodo to archive the release.
4. Copy the generated DOI into the GitHub release notes.
5. Optionally update `CITATION.cff` with the DOI in a later metadata-only commit.

Zenodo creates a DOI for each archived release. Use the release-specific DOI when citing an exact hardware version.

## Suggested Citation Text

Silva, Tiago. Senaino FT232: Educational Arduino UNO-inspired open hardware board for SENAI students. Version 1.0.0. GitHub/Zenodo.
