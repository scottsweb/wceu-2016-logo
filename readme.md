# WordCamp Europe Logo 2016

* Status: Inctive
* Contributors: [@scottsweb](http://twitter.com/scottsweb)
* Description: Logo generator for WordCamp Europe 2016 and beyond.
* Author: [Scott Evans](http://scott.ee)
* Author URI: [http://scott.ee](http://scott.ee)
* License: GNU General Public License v2.0
* License URI: [http://www.gnu.org/licenses/gpl-2.0.html](http://www.gnu.org/licenses/gpl-2.0.html)

## About

This logo generator is designed to generate a unique WordCamp Europe logo each and every year. It is an evolution of the original logos by [Tammie](https://github.com/karmatosed/wceu) and [Sonja Leix](https://github.com/sonjaleix/wceu-2015).

Each point represents a country in Europe and each line a border between them. The highlighted point is the WordCamp location for this year. Hack away - the code is open source and it would be great to keep iterating on this.

## Using the tool

* To overcome your browser security settings you will probably need to run this from a local server. The easiest way is to type: `php -S localhost:8000` from the download directory in Terminal.
* Set your settings at the top of the page and press the generate button.
* Individual points can be moved to a location of your choice.
* Double click a point to return it to a calculated/natural position.
* There is an invisble point in the middle that has a certain amount of repulsion, this can be moved too but it is tricky to grab.
* Hit the `Generate SVG` button when you are happy with the layout, this will outout the SVG code that can be imported into your favourite graphics editor.
* You will need to add your own typography to complete the design.
* The data is all stored in the `data.json` file. This contains a list of countries and the relationships between them.

## Frequently Asked Questions

...
