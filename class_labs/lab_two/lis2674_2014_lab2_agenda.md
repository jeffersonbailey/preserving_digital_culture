## Agenda:

### Web Archiving Assignment update

### Recapping Lab 1

#### What we learned
* Ontology of digital objects (physical, logical, conceptual)
* Multiple representations of digital objects
  * Can be viewed/interpreted many different way (binary, hex, text, colors, etc)
* Bitstream structure
  * The bitstream of a digital object has a certain structure -- header block, embedded metadata, content area, footer, etc -- that tells rendering software/applications what it is and thus how it can/should be rendered.
* Formats
  * "File signature" area in header can tell us what format something is even if we cannot render it
* Fixity
  * Checksums - the what the why and the how
* Organizational challenges
  * The greatest threats to digital materials are organizational/institutional not technological
* How it ties into today's work
 * Lab 1 gave context to organization challenges but our exercises were very bit-level, dealing with single files/objects and their characteristics. Lab 2 builds on that to examine preservation at the directory/drive/media level, at the descriptive level, and how these work together to become SIPs, DIPs, AIPs, and how these activities tie into high-level preservation models like OAIS, TRAC, etc.

### What we'll cover today

* OAIS / TRAC overview/review
* Acquisition & Forensics (Bitcurator)
* MODS / METS (online tool and samples)
* Packaging content (BagIt / Bagger)
* Making SIPs for repository ingest (Archivematica)
* AIPs, DIPs - discussion and online examples
* PREMIS - overview and simple exercise
* Looping back to TRAC and tie TRAC checklists to today's activities
* Brief word on donors and accessions
* Recap, relation of activities to larger archival principles, Q&A
* Links to most stuff can be found at [http://bit.ly/lis2674_lab2]

### OAIS / TRAC review

* The framework
* What the parts mean and how it identifies (and jargonizes) components
* Reviewing some TRAC areas, its link to OAIS, and some checklist stuff

### Acquisition & Forensics (Bitcurator)

* What is Bitcurator (digital forensics origins & adoption by and value to archives)
* Some caveats (write-blockers; obsolete media; file systems)
* The who, what, why of digital forensics
* Explore the interface
* Create a disk image (the what and the how)
* Analyze image/bitstream to extract certain kinds of data
* DFXML - create it and explore the what and why
* Link analysis to specific files
* Generate reports (the what and the how) and examine
* Export specific files (choose photo from relevant folder in disk image)
* Mount disk image
* Other Bitcurator tools (file similarity, metadata extractors, etc)

### MODS / METS

* Overview of standards
* MODS - for digital objects; sorta MARCish, sorta DCish
* METS - 7 sections: metsHdr, dmdSec, amdSec, fileSec, structMap, structLink, behaviorSec
* The essentials of each and some online examples
* Quick exercise using MODS generator to create a test MODS record

### Packaging content

* The BagIt specification
* The Bagger interface
* Creating & verifying bags
* Create a bag using our image and our MODS record

### SIPs

* Prepare for submission and fear not 
* Archivematica demo sandbox
* Transfer and ingest the unzipped bag sample data
* Walkthrough and explication of Archivematica microprocesses
* We have SIP!

### AIPs & DIPs

* What's the diff and what's the dealio?

### PREMIS

* Yes, more metadata - "my eyes! the goggles do nothing" for looking at XML
* Use sample PREMIS XML document and online XML editor to create a basic PREMIS record
* Discuss events and agents 

### Back on TRAC

* Talk through some of the checklist boxes in Section B "Digital Object Management"
* Discuss how what we did in Lab 1 and Lab 2 do/don't (hypothetically) meets these criteria

### Donors & Accessions

* We haven't discussed this much, so check out the book "Born Digital: Guidance for Donors, Dealers, and Archival Repositories" [pdf] [http://www.clir.org/pubs/reports/pub159/pub159.pdf]

### Recap, archival principles, Q&A

* Linking it all together, from bit-flipping to conceptual models
* Tools, argot are new but issues remain the same
* Digpres is fun b/c technologies help and hinder, contract and expand, traditional archival principles. Plus, it's a field that is transdisciplinary and always changing
* Appraisal, acquisition, description, access -- all still just as relevant re digital
* Digpres knowledge, skills, currency requires greater reliance on community of practice via colleagues, peers, drinking partners -- get out there and get involved



