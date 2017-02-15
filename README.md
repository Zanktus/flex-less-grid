# flex-less-grid
### Description
A LESS based flex grid with crossbrowser Mixins


### Installing
* Copy flex.less and grid.less into your project.
* Change the config part of the grid.less if needed.
* Include the grid.less into your main LESS-File or directly into the head (I strongly advice to use a LESS-Compiler thou).


### How to use
The naming is based on Bootstrap 3 class names. You you can use something like:
```
<div class="row">
  <div class="col-sm-4">...</div>
  <div class="col-sm-8">...</div>
</div>
```

The only additions are (## = Viewport):
* col-##-auto = auto-sizing the cols
* first-## = (on column) reorder the item to the beginning
* last-## = (on column) reorder the item to the end
* left-## = (on row) align items to the left
* center-## = (on row) align items to the center
* right-## = (on row) align items to the right
* top-## = (on row) align items to the top
* middle-## = (on row) align items to the middle
* bottom-## = (on row) align items to the bottom
* around-## = (on row) change spacing to "space-around"
* between-## = (on row) change spacing to "space-between"

### License
This project is licensed under the GNU General Public License - see the [LICENSE.md](LICENSE.md) file for details


### Credits
Coming soon...
