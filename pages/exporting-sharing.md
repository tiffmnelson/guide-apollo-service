---
title: Exporting and Sharing Annotations
description: How to export annotated genomes and share with collaborators
---

## Overview

Once you have completed annotation, you can:

1. **Export** annotated data in various formats
2. **Share** genomes with collaborators or make them public
3. **Publish** genomes for community access

## Exporting Annotations

### Export via Browser Interface

#### Step 1: Log Into Your Apollo Instance

Navigate to your Apollo Instance and log in.

#### Step 2: Select Your Organism

Click the **"Organism"** tab in the Annotator Panel and select your organism.

#### Step 3: Export Annotations

1. Click the **"Export"** button in the Annotator Panel
2. Select export format:
   - **GFF3** — Standard annotation format
   - **FASTA** — Sequence format
   - **GenBank** — GenBank format
   - **Other formats** — As available

3. Click **"Download"**

Your annotations will be downloaded to your local machine.

### Export via Command Line

If you have SSH access, you can export directly from the Apollo Instance:

```bash
# Connect to your instance
ssh -i ~/.ssh/your_private_key username@yourinstance.genome.edu.au

# Navigate to organism directory
cd /home/data/apollo_data/organism_A

# Copy annotation file to your local machine
scp -i ~/.ssh/your_private_key username@yourinstance.genome.edu.au:/home/data/apollo_data/organism_A/organism_A.gff3 ./
