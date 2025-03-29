---
title:  "Single Button Click Report PDF Generation in Dynamics 365 Sales"
date:   2025-03-28 13:25:28 -0700
categories: [d365-sales,power-platform,power-automate]
---
Generating a PDF file from an RDL (SSRS) report usually involves going to Run Report, selecting the report name, waiting for the report window to open and generate, choose Save, then Acrobat PDF, selecting the file name and saving. 

This is not exactly user friendly! Fortunately, there is a better way. This involves making the same calls as the Report Viewer to generate the report, retrieve the PDF download URL, get the PDF contents and finally trigger the file to download in the browser. 

Let's walk through it together.