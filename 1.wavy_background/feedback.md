The goal of this challange was to recreate the wavy background. 

My blue-ish background is made this way with a div that has a heigth of 60vh and a svg file right after my div.

Div and svg are placed in a container that takes the whole page, container is postioned absolute and has a z-index of -1 to be behind other content.

I did not used any flex or grid to align the two elements one after the other because div is a block element and my svg has from start a width of around 1400px.
To look almost the same as the original, I've scale the svg two times.

The svg was created usign this website: https://yqnn.github.io/svg-path-editor/
