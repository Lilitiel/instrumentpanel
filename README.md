Signalk K Instrument Panel
===============

Instrument panel implemented as a grid with draggable &amp; resizable components. Components are added dynamically eg. when the panel receives data it hasn't seen before a new cell is added to the grid.

![image](https://cloud.githubusercontent.com/assets/1049678/5593080/9657b632-91fc-11e4-9585-53e90c101149.png)


Building
================
Developing: build & watch with `npm run watch`

Building js bundle for distribution: `npm run dist` (and push changes to dist/ui.js).


To Do
=================
- [x] activate/deactivate individual widgets
- [x] connect to multiple servers
- [X] minify 
- [x] react-grid-styles: bower packaging  
- [x] 'Receiving indicator' (circle/circle-o)

- [ ] bug: start with no localstorage, unlock, drag, lock => changes not saved


- [ ] 'discovery mode' manual activation/deactivation
- [ ] delete obsolete data items, delete all
- [ ] manual addition of widgets, multiple alternative widgets
- [ ] configuration mode for widgets
- [ ] history graph widget (simple)
- [ ] history graph widget 
- [ ] configurable number of grid columns
- [ ] multiple layouts
- [ ] server configuration storage
- [ ] sailgauge widget
- [ ] ais tracker widget
- [ ] map widget
- [ ] connect to multiple servers
- [ ] ui cleanup
- [ ] per server layout
- [ ] bootstrapping from server for history graph


