# 🏥 HL7 C-CDA Clinical Document Viewer & Structured XML Summary

## 📖 About

This project demonstrates how to structure and view clinical data using **HL7 C-CDA standards** via XML formatting. It simulates a complete patient episode note, including demographic, encounter, medication, diagnosis, and social history information—rendered and validated using the **Backbeach C-CDA Viewer**.

---

## 📁 Files in the Repository

- `STANDARDS_XML_KRC.xml` – HL7 C-CDA compliant XML document containing detailed patient chart information.
- `HL7 C-CDA View_KRC.pdf` – Visualized view of the XML using [Backbeach HL7 C-CDA Viewer](https://backbeachsoftware.com.au/).
- `CDA.xsl` *(optional if included)* – Used to transform the XML file for web-based rendering.

---

## ⚙️ Project Overview

- **Patient:** Jack Dawson  
- **DOB:** April 5, 1959  
- **Summary Includes:**  
  - 🩺 Encounters  
  - 🧬 Family History  
  - 💊 Medications & Pharmacy  
  - 🧾 Problem List  
  - 🧑‍⚕️ Physical & Social History  

- **Document Standard:** HL7 C-CDA Release 2.0  
- **File Format:** XML compliant with HL7 CDA schema  
- **Diagnosis Example:** Hypertension  
- **Medications:** Telmisartan, Atenolol

---

## 📊 Key Highlights

- 🔗 Uses LOINC, SNOMED CT, and RxNorm codes for standardized clinical terminology.
- 🏷️ Contains structured data for EHR integration, suitable for care summary exchange.
- 🔍 Supports semantic validation using external HL7 XML viewers.

---

## 🧪 How to View

1. Visit the HL7 C-CDA Viewer:
   👉 [Backbeach Software Viewer](https://backbeachsoftware.com.au/challenge/home.htm)

2. Upload the XML file:  
   `STANDARDS_XML_KRC.xml`

3. Explore the interactive summary:
   - Rearrange sections
   - View medication tables
   - Check diagnosis codes and patient metadata

---

## 🛠️ How to Use in Your Own Systems

- Use the XML as a **template for generating C-CDA documents** from EHR systems.
- Validate your own documents using open-source tools or viewers like MDHT or Backbeach.
- Integrate into healthcare apps where **FHIR is not yet available**.

---

## 🔗 Related Links

- [HL7 C-CDA Standard Overview](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=492)
- [Backbeach HL7 C-CDA Viewer](https://backbeachsoftware.com.au/)
- [SNOMED CT](https://www.snomed.org/)
- [LOINC Codes](https://loinc.org/)

---

## 👨‍💻 Author

**Kalyan Raj Chinigi**  
MS in Health Informatics | EHR Specialist | Data Standards Enthusiast

