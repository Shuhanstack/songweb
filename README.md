
## songweb content organization

This folder contains all contents and supporting files to publish [songweb](https://shuhanstack.github.io/songweb/).

- `README.md`: this file. It introduces and explains the file management system of songweb
- `songweb.Rproj`: R project that is used to write and build the web
- `site_libs/`: contains js and css files that are used to define the style and interaction of the web
- `update/`: contents that I'm creating and will update in the future
  - `data_in_r/`: contains updating data analysis projects 
    - `data/`: contains original data for analysis
    - `image/`: contains image used in Rmarkdown
    - _*_`.Rmd`: Rmarkdown file for project _*_ that will not echo the code chunk; _*_ represents project name 
    - _*_`_code.Rmd`: Rmarkdown file for project _*_ that will echo the code chunk; _*_ represents project name 
    - `update.Rproj`: R project used to edit and knit Rmarkdown files
  - `paper/`: contains updating writings
- `_site.yml`: configuration file that defines website structure, including the navigation bar, theme, and links to the main web pages
- `index.html`: HTML for web home page
- `index.Rmd`: Rmarkdown for web home page that is used to generate and edit the HTML file
- `data_in_r.html`: HTML for webpage "DATA IN R" 
- `data_in_r.Rmd`: Rmarkdown for DATA IN R  that is used to generate and edit the HTML file
- `data_in_r/`: contains all support materials for DATA IN R webpage
  - `_site.yml`: configuration file that defines output document, such as HTML theme, highlight, and table of content for data analysis projects
  - `data_in_r.Rproj`: R project used to create and edit all data analysis projects
  - `data/`: contains original data for analysis
  - `image/`: contains image used in Rmarkdown files
  - `cover_image/`: contains cover image used on DATA IN R webpage for each project
  - _*_`.Rmd`: Rmarkdown file for project _*_ that will not echo the code chunk; _*_ represents project name 
  - _*_`.html`: HTML file for project _*_ that will not echo the code chunk; _*_ represents project name 
  - _*_`_code.Rmd`: Rmarkdown file for project _*_ that will echo the code chunk; _*_ represents project name 
  - _*_`_code.html`: HTML file for project _*_ that will echo the code chunk; _*_ represents project name 
- `gis.html`: HTML for webpage "GIS" 
- `gis.Rmd`: Rmarkdown for GIS webpage  that is used to generate and edit the HTML file
- `gis/`: contains materials on GIS webpage
  - `cover_image/`: contains cover image used on GIS webpage for each project

- `paper.html`: HTML for webpage "PAPER" 
- `paper.Rmd`: Rmarkdown for PAPER that is used to generate and edit the HTML file
- `paper/`: contains materials on PAPER webpage
- `gallery.html`: HTML for webpage "GALLERY" 
- `gallery.Rmd`: Rmarkdown for GALLERY that is used to generate and edit the HTML file
- `gallery/`: contains materials on GALLERY webpage
  - `_site.yml`: configuration file that defines HTML theme and highlight for project showcase
  - `gallery.Rproj`: R project used to create and edit project showcase
  - `tap_`_*_`.Rmd`: Rmarkdown file for tapestry project _*_ ; _*_ represents project name 
  - `tap_`_*_`.html`: HTML file for tapestry project _*_ ; _*_ represents project name 
  - `tap_`_*_`/`: photos of tapestry project  _*_ ; _*_ represents project name 
  - `cover_image/`: contains cover image used on GALLERY webpage for some projects
- `about_me.html`: HTML for webpage "ABOUT ME" 
- `about_me.Rmd`: Rmarkdown for ABOUT ME that is used to generate and edit the HTML file
- `about_me/`: contains materials on ABOUT ME webpage

















