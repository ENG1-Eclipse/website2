# Organisation Website

This is a [Jekyll](https://jekyllrb.com/) project designed for use with [GitHub Pages](https://pages.github.com/). This project will have content added to it as we go through our project creating a game called [Auber](https://github.com/ENG1-Group4/Auber).


## Installation

If you haven't already created your blog using Jekyll, follow the [instructions](https://jekyllrb.com/docs/) to do so from Jekyll's documentation.

NOTE: if you are using Jekyll with GitHub Pages, see the [GitHub Pages installation section](#github-pages-installation).

## Usage

### Meeting

We have chosen to store our group meetings on the site to help us see the changes. All the meetings are stored as markdown files. [Jekyll](https://jekyllrb.com/) Collections are used to dsiplay and track them. This means when creating a new meeting you need to create a new MD file with the name *YEAR*-*MONTH*-*DAY*-*MEETING TITLE*.md

The variables for each meeting are as follows, unless stated they are required: 
- `title`, the title of the meeting
- `location`, the location of the meeting
- `attendance`, who attended the meeting. This option is not required and defaults to 'All' if not set.

### Editing the Deliverables

Under the project, all the deliverables have to be displayed on the website. In order to add/edit/delete entries from the deliverables list you have to edit the deliverables.yml file inside _data folder. You can define the order and links of each of the deliverables.

- `name` defines a new unordered list item that will contain menu entries. This needs to have the text that will displayed
- each entry is marked by a `-` at the beginning of the line
- each entry has __one__ of the following attributes:
    - `url`, which  will render a link pointing to the specified URL. This is generally reserved for external links.
    - `file`, Used to link to a file. Use relative file paths for this. The existing files are stored in the assets folder.



### Customize the menu

In order to add/edit/delete entries from the main menu, you have to edit the navigation.yml file inside _data folder. Through that file you can define the structure of the menu. Take a look at the default configuration to get an idea of how it works and read on for a more comprehensive explanation.

- `title` defines a new unordered list that will contain menu entries. This has the text in each link.
- each entry is marked by a `-` at the beginning of the line
- each entry has the following attributes:
    - `url`, which  will render a link pointing to the specified URL. Note that the URL can either be relative or absolute.
    - `external`, set to true if the URL is absolute. It is worth noting that this value defaults to false if not set.
    - `sublinks`, yes, you can have a submenu inside an entries. In this way you can create nested sublists! an example of this is shown below:

```YML
- title: Support
  url: /support.html
  sublinks:
    - title: FAQ
      url: /faq.html

```
## Authors and acknowledgment
The initial versions for the site were completed by [Robert Watts](https://github.com/Robert-Watts). The rest of our ENG1 Team have contributed to the content for this site.

## Contributing
This project is not currently open for contributors outside of our organisation. 


