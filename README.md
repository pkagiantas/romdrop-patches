# romdrop-patches
What are romdrop patches? In order to create a calibration for use with both romdrop and ecuflash, you must first patch your factory rom with a matching '<calibration-id>.patch' file. Don't fret, the process is drag and drop.

1. Identify your calibration-id
2. Download associated patch
3. Launch romdrop
4. Select 'P'atch from main menu
5. Drag and drop factory rom when prompted
6. Drag and drop patch when prompted
7. Romdrop will create a newly patched binary

_Note: If no '.patch' can be found for your calibration-id, that indicates the definition for your ROM does not exist. Use Romdrop to 'R'ead your factory calibration, then submit that file for processing. Once processed, a definition and patch with be built, then added to the Romdrop repos. You can then follow the instructions above._
