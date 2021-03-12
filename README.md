# export-canvas-rubric-data
a user script for exporting canvas SpeedGrader data in the Chrome browser, based on a script created by [CUBoulder-OIT](https://github.com/CUBoulder-OIT/canvas-userscripts)

### Installation

- Install a userscript manager such as [Tampermonkey](https://www.tampermonkey.net/)
- Select Tampermonkey from the Chrome extensions dropdown menu.
- Select "Create a new script"
- In the script editor that opens, replace the default content with the content of the `export_rubric_scores.js` file from this repo.
- Select _file -> save_

### Usage

- Once installed, you should see an option in SpeedGrader to "Export Rubric Scores". 
- Clicking on this button will download a .csv file of the values entered in all rubrics for the current course. 
