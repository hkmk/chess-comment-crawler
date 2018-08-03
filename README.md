Chess Record Crawler
====

Crawling the game records of chess with human annotation from https://gameknot.com .

The records are saved as Portable Game Nortation (pgn) format. [wikipedia](https://en.wikipedia.org/wiki/Portable_Game_Notation)

## requirement
python3

python-shogi (https://github.com/niklasf/python-chess)

## usage
0. (optional) Check the parameters of get-pgn.sh

1. run get-pgn.sh

Records are saved to ./output directory.

## known problems
There are some annotations which are not written in English. (e.g. https://gameknot.com/annotation.pl?gm=52474)

## link
[ChessCommentaryGeneration](https://github.com/harsh19/ChessCommentaryGeneration)

repogitory of the first author of [Learning to Generate Move-by-Move Commentary for Chess Games from Large-Scale Social Forum Data](http://aclweb.org/anthology/P18-1154) (ACL 2018)
