# UCLUIce
This is the code repository for UCLU Ice Club's website, including style files and source code. 

## Deployment details
1. Deployed via GoDaddy hosting service via website admins only (see contact details below) at link: https://pro.godaddy.com/clients/171695 (go to Manage link next to Economy Linux Hosting with cPanel)
2. Once in cPanel, go to File Manager (under Files)
3. Select "Document root for: ucluiceclub.co.uk" option, then continue.
4. Replace files as necessary (recommended to overwrite all html files and images accordingly)

## Folder and file description
### Main pages
All main pages are stored in root directory (may migrate to separate folder later), referring to other resource folders via relative pathing (not using absolute pathing due to the hosting server's folder layout). Templatetools.html shows a list of bootstrap tools that can be easily used and adapted.

Each page has it's own style imports and navigation bar.

###  js
Contains javascript files for importing.

### css
Contains css files for importing.

### fonts
Contains font awesome files for importing.

### images
Contains image resource files. Files within this folder (and not the subfolders) are used across most, if not all, pages.
* Banner subfolder contains images used for the dynamic banner in index.html (if adding more images, make sure to change the JavaScript numberofimages variable accordingly). 
* Gallery subfolder contains images used for gallery page.
* Roster subfolder contains images used for roster page.

## Contact
* Jamie: jamie.law.14@ucl.ac.uk
* Shwe: shwe.ei.14@ucl.ac.uk
