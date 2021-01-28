# Organisation Website

This is a [Jekyll](https://jekyllrb.com/) project designed for use with [GitHub Pages](https://pages.github.com/). This project will have content added to it as we go through our project creating a game called [Auber](https://github.com/ENG1-Eclipse/Team1-Game2).


## Installation

If you haven't already created your blog using Jekyll, follow the [instructions](https://jekyllrb.com/docs/) to do so from Jekyll's documentation.

NOTE: if you are using Jekyll with GitHub Pages, see the [GitHub Pages installation section](#github-pages-installation).

## Usage

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
[Team 4:](https://github.com/eng1-group4)

The initial versions for the site were completed by [Robert Watts](https://github.com/Robert-Watts). The rest of our ENG1 Team have contributed to the content for this site.


[Team 1:](https://github.com/eng1-eclipse)

This site has been adapted to be used in Assessment 2 by [Harry Smith](https://github.com/HTS126). All team members have contributed to the deliverables and code on this website.

## Contributing
This project is not currently open for contributors outside of our organisation. 


