# wlw (Welk lidwoord)
A simple BeautifulSoup parsing script for the website welklidwoord.nl, a website to find out which article (lidwoord) belongs to a noun (zelfstandig naamword) in the Dutch language.

## Requirements
This script requires python 3.x and the BeautifulSoup4 library. It also requires an internet connection during usage.

## Installation
Clone into your $PATH and make wlw executable with `$ sudo chmod +x wlw`

## Usage
In your terminal, type `$ wlw <noun>` where <noun> is the noun for which you want to find out the corresponding article. E.g. `$ wlw auto` will return `De auto`.
