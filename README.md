# Udacity-improved-viz

Exercise to improve a visualization found in the wild.



## Image picked

First step is to pick an image to improve. The image was sourced from this impressively depressing collection of [terrible visualizations](). The image selected is displayed below: 

![Viz to improve](/img/viz.jpg)



## Strategy: 

- Remove the excess background and font color, focus the color in the data to draw attention.
- Properly plot the data points.
- Keep the scale as was. 
- Remove the red shading from underneath -- only seems to be useful in so far as it is loud and jarring. 
- Remove the numeric labels -- replace with hovering.



## Library Used: Dimple.js

To make the new visualization (which will have higher fidelity but probably look worse overall) the author has used [Dimple.js](http://dimplejs.org/), a robust viz abstraction that allows users to jump straight into charts using data. For help using Dimple.js: 

- [Examples](http://dimplejs.org/examples_index.html)
- [Advanced Examples](http://dimplejs.org/advanced_examples_index.html)
- [Full API Docs](https://github.com/PMSI-AlignAlytics/dimple/wiki)



## Future Improvements: 

- Increase the font size of the axes' labels.
- Have the svg original size be responsive to the original browser widths.
- Have the svg resize when browser width changes.
