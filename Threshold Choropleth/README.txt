This choropleth uses a threshold scale for quantization, mapping arbitrary slices of a continuous domain to discrete values in the range. Unemployment rates ranging from 2 to 10% are quantized into different shades of purple.

var color = d3.scale.threshold()
    .domain([.02, .04, .06, .08, .10])
    .range(["#f2f0f7", "#dadaeb", "#bcbddc", "#9e9ac8", "#756bb1", "#54278f"]);


http://bl.ocks.org/mbostock/3306362