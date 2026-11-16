---
title: Using JBrowse for Visualisation
description: How to view and explore genome annotations with JBrowse
---

## Overview

JBrowse is an interactive genome browser integrated into Apollo. It allows you to visualise your genome, annotations, and evidence tracks in a single interface.

For detailed instructions, see the [JBrowse User Guide](https://jbrowse.org/jb2/docs/user_guide/).

## Accessing JBrowse

JBrowse is built into Apollo. Once you have loaded a genome and created tracks, JBrowse will display:

1. **Genome sequence** (top)
2. **Annotation tracks** (middle)
3. **Evidence tracks** (bottom) — alignments, variants, coverage

![](images/apollo-service/fig4-jbrowse-interface.png)

*Fig 4. The JBrowse genome browser showing genome sequence, gene annotations, and evidence tracks.*

## Navigation

### Zoom In/Out

- Use the **zoom slider** on the left
- Use **keyboard shortcuts**: `+` to zoom in, `-` to zoom out
- **Double-click** on a region to zoom in

### Pan Left/Right

- Click and drag the genome view
- Use **arrow keys** to pan
- Use the **scroll bar** at the bottom

### Search for Features

1. Click the **search icon** (magnifying glass)
2. Type a gene name, region, or coordinate
3. Press **Enter**
4. JBrowse will navigate to the feature

Example searches:
- `gene001` — search by gene name
- `chr1:1000-2000` — search by coordinates
- `BRCA1` — search by gene symbol

## Viewing Feature Details

### Click on a Feature

1. Click on a gene, exon, or other feature in the genome view
2. A **details panel** will appear showing:
   - Feature name and type
   - Coordinates (start, end, strand)
   - Associated annotations
   - Evidence supporting the feature

### View Evidence

1. Click on an evidence track (BAM, VCF, BigWig)
2. The details panel will show:
   - Alignment details (for BAM)
   - Variant information (for VCF)
   - Coverage values (for BigWig)

## Track Management

### Show/Hide Tracks

1. Click the **track menu** (three dots) next to a track name
2. Select **"Show"** or **"Hide"**

### Reorder Tracks

1. Click and drag a track name to reorder
2. Tracks will rearrange in the display

### Change Track Display

1. Click the **track menu** (three dots)
2. Select **"Display settings"**
3. Adjust display options (colour, height, etc.)
4. Click **"Apply"**

## Exporting Views

### Take a Screenshot

1. Use your browser's screenshot tool or operating system screenshot function
2. Capture the genome view

### Export Data

See [Exporting and Sharing Annotations](/guide-apollo-service/pages/exporting-sharing) for instructions on exporting annotation data.

## Tips and Tricks

{% include callout.html type="tip" content="Use the search function to quickly navigate to genes of interest. Bookmark frequently viewed regions for easy access." %}

{% include callout.html type="tip" content="Adjust track heights and colours to improve visibility of specific features." %}

{% include callout.html type="note" content="JBrowse displays evidence tracks at different zoom levels. Zoom in to see individual reads or variants." %}

## Troubleshooting

### Issue: Tracks not displaying

**Solution**: Check that tracks are visible (not hidden). Ensure tracks are properly loaded in Apollo.

### Issue: Slow performance when zoomed in

**Solution**: This is normal for large genomes with many reads. Try zooming out or hiding unnecessary tracks.

## Next Steps

- [Exporting and Sharing Annotations](/guide-apollo-service/pages/exporting-sharing)
- [Manual Annotation](/guide-apollo-service/pages/manual-annotation)

## References

- [JBrowse User Guide](https://jbrowse.org/jb2/docs/user_guide/)
- [Apollo Documentation](https://apollo.jbrowse.org/)
