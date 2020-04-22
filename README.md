# 08Fun-with-HTML5-Canvas

This project is based on live tutorial and the following JavaScript30 project:
https://github.com/wesbos/JavaScript30/tree/master/08%20-%20Fun%20with%20HTML5%20Canvas

Live site for this project:
https://ekaterinaasf.github.io/08Fun-with-HTML5-Canvas/

## DOM

| tag name   | attributes                           | role                 |
| ---------- | ------------------------------------ | -------------------- |
| `<canvas>` | `id="draw" width="800" height="800"` | the canvas for HTML5 |

## Styling

| class name | description              | role                      |
| ---------- | ------------------------ | ------------------------- |
| `html`     | sets appropriate margins | make page more visible    |
| `body`     | sets margins             | make content more visible |

## Listeners

| type          | attached to | callback                                                    |
| ------------- | ----------- | ----------------------------------------------------------- |
| `'mousedown'` | `canvas`    | `isDrawing = true; [lastX, lastY] = [e.offsetX, e.offsetY]` |
| `'mousemove'` | `canvas`    | `draw`                                                      |
| `'mouseup'`   | `canvas`    | `() => isDrawing = false)`                                  |
| `'mousou'`    | `canvas`    | `() => isDrawing = false)`                                  |

## Handlers

| syntax   | parameters | return value | behavior                                                        |
| -------- | ---------- | ------------ | --------------------------------------------------------------- |
| `draw()` | `event`    | no           | change canvas style using `hue` depending on the mouse position |
