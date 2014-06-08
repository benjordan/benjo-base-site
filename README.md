# Base Frontend Code

A library of default styles and files for starting a project. This is a Compass based frontend framework.

Sass files are located in the sass folder and compile to the css directory

- Operations folder is built to hold you custom mixins and such
- Pages folder is used to hold one scss partial per page or section of the website. The _all.scss file is loaded into the style.scss file which compile to the final style.css file loaded into the site header
- Snippets folder also has the same partial structure as the Pages folder. Snippets tend to be used for global elements like nav or footer elements
- Variables folder is for colors and typography. Add your color and type vairables here to be used into all the other files

## Typical Use Case

When starting a new project, I download the zip and drop it into place in my sites folder. I then create a new repo for the project and do the initial commit. Then drop it into Codekit for compiling and make awesome things.
