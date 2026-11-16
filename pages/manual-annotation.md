
---

### **File 11: `pages/manual-annotation.md`**

```markdown
---
title: Performing Manual Genome Annotation
description: How to manually curate and edit genome annotations in Apollo
---

## Overview

Apollo enables real-time collaborative curation and editing of genome annotations. This guide covers the basics of manual annotation in Apollo.

For detailed instructions, see the [Apollo User's Guide](https://apollo.jbrowse.org/).

## Getting Started

### Log Into Your Apollo Instance

1. Navigate to your Apollo Instance URL (e.g., `smithlab.genome.edu.au/apollo`)
2. Log in with your credentials
3. Select your organism from the dropdown menu

![](images/apollo-service/fig3-apollo-interface.png)

*Fig 3. The Apollo interface showing the genome browser (centre), Annotator Panel (right), and navigation controls (top).*

## Basic Annotation Tasks

### Viewing Genome Features

1. Use the **zoom controls** to navigate the genome
2. **Click on features** to view details
3. Use the **search bar** to find specific genes or regions

### Creating a New Gene

1. Click the **"Create New Feature"** button
2. Select **"Gene"** from the feature type menu
3. Click and drag on the genome to define the gene boundaries
4. Fill in gene details (name, description, etc.)
5. Click **"Save"**

### Editing Gene Predictions

1. Click on an existing gene prediction
2. Click **"Edit"** in the feature details panel
3. Modify the gene boundaries, exon structure, or other properties
4. Click **"Save"**

### Adding Evidence

1. Click on a gene
2. Click **"Add Evidence"** in the feature details panel
3. Select evidence type (transcript, protein, etc.)
4. Provide evidence details
5. Click **"Save"**

### Deleting Features

1. Click on a feature
2. Click **"Delete"** in the feature details panel
3. Confirm deletion

## Collaborative Annotation

### Adding Users

Only the Project Administrator can add users:

1. Log in as Project Administrator
2. Click the **"User"** tab in the Annotator Panel
3. Click **"+ Create User"**
4. Fill in user details (name, email, password, role)
5. Assign user to groups and organisms
6. Click **"Save"**

### Assigning Permissions

1. Click the **"User"** tab
2. Select a user
3. Click the **"Groups"** tab to assign groups
4. Click the **"Permissions"** tab to assign organism access
5. Click **"Save"**

### Tracking Changes

Apollo tracks all annotation changes. To view the history:

1. Click on a feature
2. Click **"History"** in the feature details panel
3. View all edits and who made them

## Best Practices

{% include callout.html type="tip" content="Save your work frequently. Apollo auto-saves, but manual saves ensure your changes are committed." %}

{% include callout.html type="note" content="Use consistent naming conventions for genes and features across your genome. This makes downstream analysis easier." %}

{% include callout.html type="important" content="Communicate with your team about which regions you are annotating to avoid duplicate work." %}

## Troubleshooting

### Issue: Cannot edit a feature

**Solution**: Check that you have the correct permissions for that organism. Contact your Project Administrator if you need access.

### Issue: Changes not saving

**Solution**: Ensure you have clicked the "Save" button. Check your internet connection and try again.

## Next Steps

- [Using JBrowse for Visualisation](/guide-apollo-service/pages/jbrowse-visualisation)
- [Exporting and Sharing Annotations](/guide-apollo-service/pages/exporting-sharing)

## References

- [Apollo User's Guide](https://apollo.jbrowse.org/)
- [Apollo Training Resources](https://apollo-portal.genome.edu.au/resources)
