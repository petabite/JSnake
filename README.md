# JSnake

super plain vanilla javascript snake

![demo](https://raw.githubusercontent.com/petabite/JSnake/master/jsnake.png)

## How to Play

1. clone repo
2. open `jsnake.html` in your fav browser
3. have fun!

## Game Configuration

change these parameters to your liking

**html**

```html
<!--you can change the size of the canvas!-->
<canvas id="snake" width="500" height="500"></canvas>
```

**js**

```javascript
const CANVAS_ID = "snake"; // id of canvas to render game in
const GAME_SPEED = 250; // in ms
const SNAKE_SIZE = 25; // width of cell in grid in pixels
const CANVAS_COLOR = "#000000"; // background color
const FOOD_COLOR = "#FF0000";
const SNAKE_COLOR = "#00FF00";
const SNAKE_BORDER_COLOR = "#007a1d";
const SNAKE_BORDER_SIZE = 3; // width of border in pixels
```

Feel free to embed on your own site!
