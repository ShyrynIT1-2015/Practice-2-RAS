# In this practice work we use js animation to create our Website.
We create 3 html file and 1 css file. Also 1 js file. Use containers to create 6 boxes. And they have also background containers.

## We changed the width and height and also added div flexbox so that they were on the same level.We have a lot of containers like
-background-container
-cell-container
-containercontainer
-container
-report-container

Then we create them for help css files. We add like
  width: 50%;
    border: 3px solid hsl(236, 100%, 87%);
    border-radius: 100px;
    margin-bottom: 3vh;

### We create operators like var
var CanvasXSize = 100;
var CanvasYSize = 80;
var speed = 30; //lower is faster
var scale = 0.12;
var y = -4.5; //vertical offset

// Main program

var dx = 0.75;
var imgW;
var imgH;
var x = 0;
var clearX;
var clearY;
var ctx;

to create animation. For help this we can move our images. We did it from JS.
We also create text
  <p class="xl-text">0hr <!--daily--></p>
          <p class="small-text">Previous - 1hr <!--daily--></p>
        </div>
        <!-- daily
        Previous - 1hr daily
        2hrs weekly
        Previous - 2hrs weekly
        7hrs monthly
        Previous - 11hrs monthly -->
      </div>

      We use divs to be more not confusing.