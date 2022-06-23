This project is my Muliple lines Graph project in HTML, CSS and JavaScript. 

Throgh this project consist the following:

  1. HTML, CSS & JavaScript



Multiple lines Graph is a HTML, CSS and JavaScript-based charts.
* I have added a link to the providing CDN (Content Delivery Network):
  <script
 src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.5.0/Chart.min.js">
</script>
* Then added a <canvas> to where I want to draw the charts:
<canvas id="myChart" style="width:100%;max-width:900px"></canvas>
* The canvas element must have a unique id.
* Typical Line Charts Syntax:
new Chart("myChart", {
  type: "line",
  data: {
    labels: xValues,
    datasets: [{ 
      data: [],
      borderColor: "black",
      fill: false
    }, {
* Total Confirmed Cases is represented by the colour: BLACK
* Total Deaths is represented by the colour: Red
* Total Recovered is represented by the colour: Blue
* Active Cases is represented by the colour: Pink
* Daily Confirmed Cases is represented by the colour: Green
* Daily Deaths is represented by the colour: Purple 

NB
The code can be copied and be tried on Tryit Editor v3.7
Link: https://www.w3schools/html/tryit.asp?filename=tryhtml_intro
