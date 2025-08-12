# Azure Document Intelligence – Philippine Birth Certificate Analysis

This mini-project explores the capabilities of **Azure AI Document Intelligence** in parsing official Philippine birth certificates. Using the prebuilt document model, I analyzed 8 scanned certificates and successfully extracted key fields such as **my mother’s name** and **her date of birth** with high confidence.

## Objective

To validate Azure’s ability to:
- Recognize and extract structured data from local civil documents
- Support future automation for ID verification, DTI loan applications, and lifeline features in Project Elentiya

## Methodology

- **Tool Used:** Azure AI Document Intelligence Studio (Free Tier)
- **Document Type:** Scanned birth certificates from the Office of the Local Civil Registrar
- **Model:** Prebuilt Document Model
- **Limitations:** Free tier capped at 8 documents

## Results

| Field Extracted     | Sample Value             | Confidence |
|---------------------|--------------------------|------------|
| FirstName (Mother)  | MELITUNA                 | High       |
| LastName (Mother)   | NAPALIT                  | High       |
| DateOfBirth         | SEPTEMBER 07, 1957       | High       |
| DocumentNumber      | 1999-256                 | Medium–High |

##  Insights

- The model accurately parsed **key-value pairs** from official Philippine formats
- Names and birthdates were consistently extracted across all samples
- Custom model training could improve extraction of fields like **place of birth**, **citizenship**, and **registry remarks**

## Next Steps

- Train a **custom model** using labeled birth certificate data
- Integrate extraction into a **business automation pipeline**
- Use results to support **DTI loan documentation** and **Project Elentiya’s lifeline verification**

##  Reflections

This project is part of my broader mission to blend **technical rigor** with **empathy-driven design**. Every document parsed is a step toward **liberating my family from manual processes**, and building tools that honor identity, legacy, and safety.

---
