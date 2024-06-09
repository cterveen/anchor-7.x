## Project title

anchor-7.x

## Description
anchor-7.x is a Drupal 7 module that that adds index functionality to Drupal books. Although search functions can be useful to find certain items an index will lead to the correct description instantly. The index is also exported to a printable version by bookrtf-7.x.

The module can be considered an alpha version. The coding was not brought to standards. The RTF document was tested in Microsoft Word en Libre Office writer. Options are available. A (useful) help page is not available, but some details are in help.md. Internationalisation and localisation is not available. The module is not in the Drupal module repository.

The project is currently being used and works well. Further development is not intended.

The module has been ported to Drupal 9.x: [bookindex9.x](https://github.com/cterveen/bookindex-9.x)

## Installation

Depends on the Drupal [Book](https://www.drupal.org/project/book) module which is part of Drupal Core

Download [Simple HTML DOM](https://simplehtmldom.sourceforge.io/) and copy it into libraries://simple_html_dom/

Copy all the files into modules://anchor/

Enable the module

## Use

Add terms into your book pages by adding an anchor in the book page with the name index[Keyword].

The index can be accessed by book/index/[node]

## Credits

Depends on:

- Drupal <https://www.drupal.org/>
- Drupal book <https://www.drupal.org/project/book>
- Simple HTML DOM <https://simplehtmldom.sourceforge.io/>

## License

To be decided
