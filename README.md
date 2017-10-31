# OJS3 XML workflow

## Copyediting
1. Technical cleanup of DOCX
2. Revise article metadata in OJS

## Production
1. Convert production ready DOCX to XML using Markup plugin (https://github.com/kaschioudi/ojs3-markup)
2. Open the ready JATS XML file in a editor (XML editor or text editor like Notepad++)
3. ~~Create the front section of the JATS XML file with jatsFrontPuller plugin (https://github.com/ajnyga/JatsFrontPuller).~~ Not needed anymore after these additions to the markup-plugin https://github.com/kaschioudi/ojs3-markup/pull/31
4. Clean and check the body and back sections manually
5. Upload the ready XML galley to OJS
6. If needed, create the PDF file with cassiusPrinter plugin (forthcoming)

## Publishing
Visualizing JATS XML:
- lensGalley (https://github.com/ajnyga/lensGalley)
- embedGalley (https://github.com/ajnyga/embedGalley)













