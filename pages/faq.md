
---

### **Page 7: pages/faq.md**

```markdown
---
title: Frequently Asked Questions
description: Common questions and troubleshooting for the Australian Apollo Service
---

## Application and Access

### How do I sign up for an Apollo Instance?

See [Accessing the Australian Apollo Service](#accessing-the-service) for step-by-step instructions.

### How long does approval take?

Approval typically takes **3–5 business days**. You will receive an email confirmation once your instance is created.

### Do I need a Nectar account?

[AUTHOR TO CLARIFY: Do users need existing Nectar accounts, or is one provisioned for them?]

### What are the eligibility requirements?

- You must be an Australian-based researcher
- You must be affiliated with a recognised Australian academic or research institute
- Your Principal Investigator must authorise the request

### Can I apply for multiple instances?

[AUTHOR TO CLARIFY: Can research groups have multiple instances?]

---

## Data Preparation and Upload

### What file formats does Apollo support?

See [Loading Genomes and Annotation Files](#loading-genomes) for a complete list of supported formats.

### What is the file size limit?

- **Browser upload**: ≤2 GB per file
- **Command-line upload**: No limit (recommended for files >2 GB)

### How do I prepare my data files?

See [Step 1: Prepare Your Data Files](#step-1-prepare-your-data-files) in the Loading Genomes guide.

### My BAM file is not displaying correctly. What should I do?

Check that reference sequence headers in your BAM file do not contain spaces. Use the `samtools reheader` command to fix headers if needed. See [Prepare Evidence Files](#prepare-evidence-files) for instructions.

### How long does it take to upload a large genome?

Upload time depends on file size and internet connection speed. Large files (>10 GB) may take several hours. Use the command-line method for faster, more reliable uploads.

### Can I upload data directly from a public repository?

[AUTHOR TO CLARIFY: Can users download directly from NCBI, Ensembl, etc., or must they download locally first?]

---

## Annotation and Curation

### How do I manually annotate my genome?

See [Performing Manual Genome Annotation](#manual-annotation) for step-by-step instructions.

### Can multiple users annotate the same genome?

Yes. The Project Administrator can add multiple users and assign them permissions for specific organisms. Apollo tracks all changes and prevents conflicts.

### How do I undo an annotation change?

Click on a feature and select **"History"** to view all edits. You can revert to a previous version if needed.

### What is the difference between a gene and an mRNA?

- **Gene**: A genomic region containing one or more transcripts
- **mRNA**: A transcript produced from a gene

In Apollo, genes contain mRNAs, which contain exons and CDSs.

---

## Visualisation and Export

### How do I view my annotations in JBrowse?

Once you have loaded a genome and created tracks, JBrowse will display automatically. See [Using JBrowse for Visualisation](#jbrowse-visualisation) for navigation tips.

### Can I export my annotations?

Yes. See [Exporting Annotations](#exporting-annotations) for instructions.

### What export formats are available?

Common formats include GFF3, FASTA, and GenBank. See [Exporting Annotations](#exporting-annotations) for details.

### How do I share my genome with collaborators?

See [Sharing Genomes](#sharing-genomes) for instructions on adding users and making genomes public.

---

## Troubleshooting

### My Apollo Instance is running slowly. What can I do?

- Close unnecessary browser tabs
- Clear your browser cache
- Try a different browser
- Contact the Apollo Service Team if the issue persists

### I cannot log into my Apollo Instance. What should I do?

- Check that your username and password are correct
- Ensure your internet connection is working
- Try resetting your password
- Contact the Apollo Service Team at [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au)

### My genome tracks are not displaying. What should I do?

- Ensure all mandatory files (FASTA, FAI, GFF3, GFF3.gz) are present
- Check that files are properly formatted and indexed
- Try re-uploading the files
- See [Troubleshooting](#troubleshooting) in the Loading Genomes guide

### I have a question not answered here. Who should I contact?

Email the Apollo Service Team at [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au) or see [Contact Us](#contact).

---

## References

- [Apollo Documentation](https://apollo.jbrowse.org/)
- [JBrowse User Guide](https://jbrowse.org/jb2/docs/user_guide/)
- [Australian Apollo Service](https://apollo-portal.genome.edu.au/)
