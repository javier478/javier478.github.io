function cubeD3(id, width, height)
{

    var svg = d3.select(id);
    // Add SVG canvas
    svgcanvas = svg.append("svg:svg")
        .attr("width", 325)
        .attr("height", 250);
     
    // Background dark gray rectangle
    svgcanvas.append("svg:rect")
        .attr("x",0)
        .attr("y",0)
        .attr("width",325)
        .attr("height",250)
        .style("fill", "rgb(125,125,125)");

}