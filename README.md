## Project title

anchor-7.x

## Description
anchor-7.x is a Drupal 7 module that that adds index functionality to Drupal books. Although search functions can be useful to find certain items an index will lead to the correct description instantly. The index is also exported to a printable version by bookrtf-7.x.

The module can be considered an alpha version but is being used and works well. The coding was not brought to standards. The RTF document was tested in Microsoft Word en Libre Office writer. Options are available. A (useful) help page is not available, but some details are in help.md. Internationalisation and localisation is not available. The module is not in the Drupal module repository.

This module is archived. The module has been ported to Drupal 9.x: [bookindex9.x](https://github.com/cterveen/bookindex-9.x)

## Installation

Depends on the Drupal [Book](https://www.drupal.org/project/book) module which is part of Drupal Core

Download [Simple HTML DOM](https://simplehtmldom.sourceforge.io/) and copy it into libraries://simple_html_dom/

Copy all the files into modules://anchor/

Enable the module

## Use

Add terms into your book pages by adding an anchor in the book page with the name index[Keyword].

The index can be accessed by book/index/[node]

## Credits

Written by Christiaan ter Veen <https://www.rork.nl/>

Depends on:

- Drupal <https://www.drupal.org/>
- Drupal book <https://www.drupal.org/project/book>
- Simple HTML DOM <https://simplehtmldom.sourceforge.io/>

## License

anchor-7.x is licensed under the GNU General Public License, version 2 or later. That means you are free to download, reuse, modify, and distribute any files in this repository under the terms of either the GPL version 2 or version 3, and to run this module in combination with any code with any license that is compatible with either versions 2 or 3.
http://www.gnu.org/licenses/old-licenses/gpl-2.0.html
