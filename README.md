# Lund_Uni_Quarto
This repo contains the templates for Quarto documents and presentations for Lund University based on their online template. Please be aware that this is still a rough beta version and compatability with all Quarto features have not been tested.

### Description
I currently have a very rough beta version of a presentation template which can be used to create presentations that resemble the offical power point template from Lund Universiy. All necessary file are in the 'extensions' folder and need to placed in the project folder of the Quarto presentation. The SCSS file (lund_pres_theme) contains all relevant styling options for the presentation. One can tweak options such as font size or colors here. The png files contain the logo and the background image for the title slide. The file 'clean_title_page.html' is needed to remove unncessary elements from the title slide.
THe rest follows the same procedures as a normal quarto presentation, eg. specfing Title and author in the YAML.

### Current issues
- Change color and size of slide-menu-button. I can change the color of all links in the presentation but somehow not of only the slide menu button. I can also not change its size even though I successfully moved it to the top right corner.
- Clean up code and reduce redundant code
- External YAML
- Make package easily downloadable for others to use
- Create Quarto document template
