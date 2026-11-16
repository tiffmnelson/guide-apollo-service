---
title: Frequently Asked Questions
description: Common questions and troubleshooting for the Australian Apollo Service
---

## Application and Access

### How do I sign up for an Apollo Instance?

See [Accessing the Australian Apollo Service](/guide-apollo-service/pages/accessing-the-service) for step-by-step instructions.

### How long does approval take?

Approval typically takes **3–5 business days**. You will receive an email confirmation once your instance is created.

### Do I need a Nectar account?

Your Apollo Instance is hosted on the Nectar Research Cloud. Access credentials will be provided by the Apollo Service Team once your instance is created. You do not need a pre-existing Nectar account.

### What are the eligibility requirements?

- You must be an Australian-based researcher
- You must be affiliated with a recognised Australian academic or research institute
- Your Principal Investigator must authorise the request

### Can I apply for multiple instances?

Yes, research groups can apply for multiple instances if needed. Each instance will have its own URL and management structure. Contact [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au) to discuss your requirements.

---

## Data Preparation and Upload

### What file formats does Apollo support?

See [Loading Genomes and Annotation Files](/guide-apollo-service/pages/loading-genomes) for a complete list of supported formats.

### What is the file size limit?

- **Browser upload**: ≤2 GB per file
- **Command-line upload**: No limit (recommended for files >2 GB)

### How do I prepare my data files?

See [Step 1: Prepare Your Data Files](/guide-apollo-service/pages/loading-genomes#step-1-prepare-your-data-files) in the Loading Genomes guide.

### My BAM file is not displaying correctly. What should I do?

Check that reference sequence headers in your BAM file do not contain spaces. Use the `samtools reheader` command to fix headers if needed. See [Prepare Evidence Files](/guide-apollo-service/pages/loading-genomes#prepare-evidence-files) for instructions.

### How long does it take to upload a large genome?

Upload time depends on file size and internet connection speed. Large files (>10 GB) may take several hours. Use the command-line method for faster, more reliable uploads.

### Can I upload data directly from a public repository?

You can download genome data from public repositories (NCBI, Ensembl, etc.) to your local machine, then upload to Apollo. Alternatively, if you have command-line access to your Apollo Instance, you can download directly to the instance using `wget` or `curl`.

---

## Annotation and Curation

### How do I manually annotate my genome?

See [Performing Manual Genome Annotation](/guide-apollo-service/pages/manual-annotation) for step-by-step instructions.

### Can multiple users annotate the same genome?

Yes. The Project Administrator can add multiple users and assign them permissions for specific organisms. Apollo tracks all changes and prevents conflicts through its collaborative annotation system.

### How do I undo an annotation change?

Click on a feature and select **"History"** to view all edits. You can revert to a previous version if needed. Contact your Project Administrator if you need help with version control.

### What is the difference between a gene and an mRNA?

- **Gene**: A genomic region containing one or more transcripts
- **mRNA**: A transcript produced from a gene

In Apollo, genes contain mRNAs, which contain exons and CDSs (coding sequences).

### How do I add evidence to support my annotations?

See [Adding Evidence](/guide-apollo-service/pages/manual-annotation#adding-evidence) in the Manual Annotation guide for instructions.

---

## Visualisation and Export

### How do I view my annotations in JBrowse?

Once you have loaded a genome and created tracks, JBrowse will display automatically. See [Using JBrowse for Visualisation](/guide-apollo-service/pages/jbrowse-visualisation) for navigation tips.

### Can I export my annotations?

Yes. See [Exporting Annotations](/guide-apollo-service/pages/exporting-sharing#exporting-annotations) for instructions.

### What export formats are available?

Common formats include:
- **GFF3** — Standard annotation format (recommended)
- **FASTA** — Sequence format
- **GenBank** — GenBank format
- Other formats may be available depending on your Apollo version

See [Exporting Annotations](/guide-apollo-service/pages/exporting-sharing#exporting-annotations) for details.

### How do I share my genome with collaborators?

See [Sharing Genomes](/guide-apollo-service/pages/exporting-sharing#sharing-genomes) for instructions on adding users and making genomes public.

### Can I make my genome publicly available?

Yes. See [Make Genome Public](/guide-apollo-service/pages/exporting-sharing#make-genome-public) for step-by-step instructions. Public genomes are read-only unless users have login credentials.

---

## Troubleshooting

### My Apollo Instance is running slowly. What can I do?

- Close unnecessary browser tabs
- Clear your browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Try a different browser (Chrome, Firefox, Safari)
- Disable browser extensions that might interfere
- Contact the Apollo Service Team if the issue persists: [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au)

### I cannot log into my Apollo Instance. What should I do?

- Check that your username and password are correct
- Ensure your internet connection is working
- Try resetting your password (if available)
- Check that your IP address is not blocked by your institution's firewall
- Contact the Apollo Service Team at [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au)

### My genome tracks are not displaying. What should I do?

- Ensure all mandatory files (FASTA, FAI, GFF3, GFF3.gz) are present
- Check that files are properly formatted and indexed
- Try re-uploading the files
- See [Troubleshooting](/guide-apollo-service/pages/loading-genomes#troubleshooting) in the Loading Genomes guide

### I'm getting an error when uploading files. What should I do?

- Check file formats are correct (see [Required File Formats](/guide-apollo-service/pages/loading-genomes#required-file-formats))
- Ensure files are not corrupted
- Try uploading via command line instead of browser (for large files)
- Contact the Apollo Service Team if the issue persists

### How do I request additional storage or resources?

Contact the Apollo Service Team at [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au) with details of your requirements.

### How do I shut down my Apollo Instance?

Only the Project Administrator can request instance shutdown. Contact the Apollo Service Team at [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au) with your instance name and request.

---

## General Questions

### How do I cite the Apollo Service in my publications?

See [How to Cite](/guide-apollo-service/about#how-to-cite) on the About page for the standard acknowledgement statement.

### Is there training available for using Apollo?

Yes. See the [Apollo Training Resources](https://apollo-portal.genome.edu.au/resources) page for tutorials, videos, webinars, and courses.

### Can I use Apollo for non-research purposes?

The Australian Apollo Service is intended for Australian-based research. Contact [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au) to discuss your specific use case.

### What happens to my data if I stop using the service?

You can export your annotated genomes at any time. See [Exporting Annotations](/guide-apollo-service/pages/exporting-sharing#exporting-annotations) for instructions. If you request instance shutdown, you will have time to export your data before the instance is removed.

### Is there a data retention policy?

Contact the Apollo Service Team at [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au) for information about data retention policies.

---

## I Have a Question Not Answered Here

If you have a question not answered in this FAQ, please contact the Apollo Service Team:

**Email**: [apollo-support@genome.edu.au](mailto:apollo-support@genome.edu.au)

**Website**: [Australian Apollo Service Portal](https://apollo-portal.genome.edu.au/)

---

## References

- [Apollo Documentation](https://apollo.jbrowse.org/)
- [JBrowse User Guide](https://jbrowse.org/jb2/docs/user_guide/)
- [Australian Apollo Service](https://apollo-portal.genome.edu.au/)
