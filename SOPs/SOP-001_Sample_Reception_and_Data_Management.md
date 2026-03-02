## 1. Purpose
To standardize the registration, inventory, tracking, and molecular processing of samples received at Mahaliana Laboratory using the Airtable database system.

## 2. Scope
Applies to all biological samples received from:
  * veterinarians
  * research collaborators
  * surveillance programs
  * conservation projects
  * diagnostic submissions

## 3. Data Management Platform
All samples are recorded in the Mahaliana Airtable database, which contains interconnected tables:
  -Accession Table
  -Customers
  -Biomedical data
  -Sample Inventory
  -DNA/RNA
  -PCR
  -Sequencing
  -Serology
  -Hematology
  -Parasitology

Each laboratory action must be recorded in Airtable to ensure traceability.

## 4. Workflow Overview for PCR analysis
              Sample reception
                    ↓
            Accession creation
                    ↓
      Sample inventory registration
                    ↓
            Metadata completion
                    ↓
            DNA/RNA extraction
                    ↓
        Automatic record creation
                    ↓
              PCR analysis
                    ↓
            PCR results entry

## 5. Step-by-Step Procedure
# 5.1 Accession Number Creation
Before any sample is processed:
  -Open Airtable → Accession Table
  -Create a new accession record (this will automatically create accession number following order) 

✅ Every sample MUST belong to an accession.

# 5.2 Sample Inventory Coding System
Each submitted sample receives a unique code: **XXXYY.ZZ**
  -XXX:	Location or source abbreviation	(PIV for Plateforme d'Information Vétérinaire which is used for all samples submitted by clinician veterinarian working on domestic animals;
  BET for sample from Betampona Natural Reserve; etc)
  -YY:	Sampling year (last two digits)
  -ZZ:	Submission order number	01

Examples
  -PIV24.01 → sample number one from veterinarian in 2024
  -BET23.15 → Betampona sample number 15 in 2023

# 5.3 Sample Registration (Inventory Table)
When registering the sample:
  -click "sample inventory form" in the left view section list inside the Sample Inventory tab, and click open form, which will lead you directly to your browser
  -Manually enter the sample unique code
  -Link the sample to its accession
  -Fill required metadata: reception date, sample type (blood, feces, swab, tissue, etc), host species, storage location (freezer ID, sample box, spot in the sample box)

# 5.4 DNA/RNA Extraction Tracking
After extraction: 
  >Go to Sample Inventory tab
  >Check the column: Extracted ✅ (This automatically creates a linked record in DNA/RNA table)

This ensures:
✅ extraction traceability
✅ avoids duplicate entries
✅ connects PCR results later

# 5.5 PCR Result Entry
PCR results must ONLY be entered from samples present in the DNA/RNA table

Procedure:
  >Open PCR tab
  >In the left view section, click PCR result form and click open form (that leads you to your browser)
  >Enter: Date, DNA/RNA sample, accession number, target pathogen/gene, result (Positive/Negative)
  >Submit (this will create record at the PCR tab)

# 6. Quality Control Rules
  -No extraction without accession number.
  -No PCR without extraction record.
  -No reporting without PCR entry.
  -All steps must be traceable in Airtable.

