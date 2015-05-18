To get started

```
$ npm i
$ gulp
$ cp node_modules/gulp-traceur/node_modules/traceur/bin/traceur-runtime.js ./dist/javascript
```

Tasks:

1. Implement blockClicked to recursively remove (or hide) all blocks of the same colour that are connected to the target element.
2. Redraw the grid moving empty blocks are moved to the top of each column.
3. Ensure blockClicked still correctly calculates neighbours after removing blocks.

Similar to Tetris but you have to click a block to have matching blocks removed.

Feel free to use whatever libs you need to make it work.

E.g.,

Given:

```
#######
###$$##
###$##$
##$$###
```

After the first $ is clicked the board should look like this:

```
##   ##
### ###
### ##$
#######
```

Clicking and of the # will result in:

```



     $
```
