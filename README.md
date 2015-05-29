# Markdown PDF
A simple way to generate Markdown files to HTML & PDF
## Installation
```bash
git clone https://github.com/nickurt/markdown-pdf.git
cd markdown-pdf
curl -sS https://getcomposer.org/installer | php
php composer.phar install
```
## Generate
```bash
bin/markdown-pdf g --help
Usage:
 g src des

bin/markdown-pdf g /path/to/source/markdown.md /path/to/output/directory
```
## Credits
Forked & cleanup version of [mre/karban](https://github.com/mre/karban) & [tyler-king/markdown-invoice](https://github.com/tyler-king/markdown-invoice)