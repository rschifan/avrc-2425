Visualizes flights between airports in the continental United States using edge bundling. The code can be easily modified to either show the top 50 airports by degree or the highest degree airport in each state.

This example combines our map and graph visualizations together in a single visualization. It demonstrates map projections, topojson, force-directed layouts, and edge bundling.

## API Links

The following links may be useful for understanding this example:

- [d3.geoAlbers()](https://github.com/d3/d3-geo#geoAlbers)
- [d3.geoContains()](https://github.com/d3/d3-geo#geoContains)
- [projection.fitExtent()](https://github.com/d3/d3-geo#projection_fitExtent)
- [topojson.feature()](https://github.com/topojson/topojson-client/blob/master/README.md)
- [topojson.mesh()](https://github.com/topojson/topojson-client/blob/master/README.md#mesh)
- [d3.nest()](https://github.com/d3/d3-collection#nests)
- [d3.curveBundle()](https://github.com/d3/d3-shape#curveBundle)
- [d3.forceSimulation()](https://github.com/d3/d3-force)

## Inspirations

The original data for this example is from the [Voronoi Arc Map](https://bl.ocks.org/mbostock/7608400) bl.ock and the [Airports](http://mbostock.github.io/d3/talk/20111116/airports.html) example by Mike Bostock.

The [Flight Patterns](http://www.aaronkoblin.com/work/flightpatterns/) work by Aaron Koblin and [Force Directed Edge Bundling for Graph Visualization](https://doi.org/10.1111/j.1467-8659.2009.01450.x) paper by [Danny Holten](http://www.win.tue.nl/vis1/home/dholten/#research) and Jarke J. van Wijk are also inspirations for this example.
