# IATI - Google Firestore Cloud Database

**IATI** is an open data sharing standard and technical framework widely used across the humanitarian community by over 1000 organizations to report aid activities, transactions and results in granular detail. It is managed by the [International Aid Transparency Initiative](https://iatistandard.org/en/), supported by the United Nations and mandated by many government development agencies.

Organizations report aid activities in compliance with IATI by converting activity information into machine readable XML code. Then organizations file and publish the information on their web servers and send file metadata to the [IATI Registry](https://www.iatiregistry.org/). For example, here is an [XML file](http://iati.oxfam.org.uk/xml/oxfamgb-al.xml) published by [Oxfam GB](https://www.oxfam.org.uk/) containing information on 9 aid activities in Albania.

**Humanitarian AI** community members are exploring setting up and storing a copy of IATI's entire corpus in a Google Cloud **Firestore** database.

### IATI Data on Dropbox
![Organization Data Folders](https://github.com/Humanitarian-AI/IATI-Firestore/blob/master/Media/IATI_Org_Folders.png)

A daily snapshot of all IATI data is stored on Dropbox and IATI updates the corpus every 24 hours. The data is stored in hundreds of individuals folders organized by publishing organizations. Information on accessing the data is located [here](https://github.com/codeforIATI/iati-data-dump).

The [Dropbox Extractor](https://github.com/Humanitarian-AI/IATI-Extractor) will systematically extract XML data stored in organization folders and export the data to the Google Cloud Firestore database.

## Firestore Database

Stay tuned for more information!
