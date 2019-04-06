# Chemistry Add-in for Word

[Chem4Word](https://www.chem4word.co.uk/) enables you to create chemical structures directly in Microsoft Word.
Not only can you draw your own structures, but you can import structures from PubChem and Opsin as well as from your own files.

The Chem4Word add-in allows the user to interact with chemistry in a document as follows

* Edit / draw your structures using an embedded open source chemical structure editor called ChemDoodle Web Sketcher.
* Edit textual descriptors for a structure.
* Import chemical structures from web services such as PubChem and Opsin.
* Import files in CML or MDL Molfile format.
* Export drawn or imported structures in CML or MDL Molfile format. You can use this option to copy drawings to other documents of share them with colleagues.
* Save structures to a personal library (using SQLite).

## How the Chem4Word Add-In works
The Chem4Word add-in stores the chemical structures as Chemical Mark-up Language (CML) inside Word documents as Custom XML Parts.
Each structure can be visualised inside a Word document with a Word Custom Control containing either a 2D format as an image constructed as DrawingML (using the Open XML SDK 2.5 for Office) or a 1D format using one of its textual descriptors as text.
When you edit a chemistry structure and save the results, all of its linked visualisations are also updated.
A web service is used to generate a code known as an InChiKey, this uniquely identifies the structure, the InChiKey is stored as an additional textual descriptor element inside the CML.

One big advantage of having the chemistry embedded as machine readable XML is that the data is very easily imported into other information systems such as SharePoint, allowing unique chemical structures to be catalogued as documents are imported and subsequently searched for.

## Project Details
* [Website](https://www.chem4word.co.uk/)
* [Version 2 Source Code](https://github.com/Chem4Word/Version2)
* [Version 3 Source Code](https://github.com/Chem4Word/Version3)
* [Version 3.1 Source Code](https://github.com/Chem4Word/Version3-1)
* Project License Type: [Apache 2.0](https://github.com/Chem4Word/Version3/blob/master/Licence.md)
* Project Main Contacts: [Clyde Davies](https://github.com/deadlyvices), [Mike Williams](https://github.com/MikeWilliams-UK) 

## Other information
Our installer is built using the WiX Toolset.

We use xUnit.net for our Unit Testing.

## Quicklinks
* [Blog](https://www.chem4word.co.uk/category/news/)
* [Documentation](https://www.chem4word.co.uk/)
* [Contribute](https://github.com/Chem4Word/Version3)
