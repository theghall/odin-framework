## For the Odin Project
### Implement a simple 12 column Framework.  View [Sample](https://theghall.github.io/odin-framework/example/index.html)
### To use, first create a container div with the class of ```grid_12```, which sets up a 960px wide container.
### ```row``` starts a new row.
### A single column is 60px wide with a 20px gutter. Within a row you create div containers using ```class-wd-n``` where n is a number from 1-12.  All the n's must add up to 12.

### In the following example we have 3 container divs within the ```grid_12``` container with a width of 300px each.
```
   <div class="grid_12">
      <div class="row">
        <div class="col-wd-4">
        </div>
        <div class="col-wd-4">
        </div>
        <div class="col-wd-4">
        </div>
      </div>
   </div>
```
