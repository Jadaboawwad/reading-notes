## 1.  Chart.js API.

        in this part we will discuss the following points

* What is Chart.js API.
* Give example of implemntation.
* What is the documentaion link for it.
<br/>

                           The beginning of Part One

### 1.1: what chart.js is:

JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page, It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

### 1.2 : The documention Link for it:

## [Documetaion link](https://www.chartjs.org/docs/latest/)

### 1.3: Example for implemation:

## explaind in the link : [Link](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <title>Chart.js demo</title>
    <!-- import plugin script -->
    <script src='Chart.min.js'></script>
</head>

<body>
    <!-- line chart canvas element -->
    <canvas id="buyers" width="600" height="400"></canvas>
    <!-- pie chart canvas element -->
    <canvas id="countries" width="600" height="400"></canvas>
    <!-- bar chart canvas element -->
    <canvas id="income" width="600" height="400"></canvas>
    <script>
        // line chart data
        var buyerData = {
            labels: ["January", "February", "March", "April", "May", "June"],
            datasets: [{
                fillColor: "rgba(172,194,132,0.4)",
                strokeColor: "#ACC26D",
                pointColor: "#fff",
                pointStrokeColor: "#9DB86D",
                data: [203, 156, 99, 251, 305, 247]
            }]
        }
        // get line chart canvas
        var buyers = document.getElementById('buyers').getContext('2d');
        // draw line chart
        new Chart(buyers).Line(buyerData);
        // pie chart data
        var pieData = [{
                value: 20,
                color: "#878BB6"
            },
            {
                value: 40,
                color: "#4ACAB4"
            },
            {
                value: 10,
                color: "#FF8153"
            },
            {
                value: 30,
                color: "#FFEA88"
            }
        ];
        // pie chart options
        var pieOptions = {
            segmentShowStroke: false,
            animateScale: true
        }
        // get pie chart canvas
        var countries = document.getElementById("countries").getContext("2d");
        // draw pie chart
        new Chart(countries).Pie(pieData, pieOptions);
        // bar chart data
        var barData = {
            labels: ["January", "February", "March", "April", "May", "June"],
            datasets: [{
                    fillColor: "#48A497",
                    strokeColor: "#48A4D1",
                    data: [456, 479, 324, 569, 702, 600]
                },
                {
                    fillColor: "rgba(73,188,170,0.4)",
                    strokeColor: "rgba(72,174,209,0.4)",
                    data: [364, 504, 605, 400, 345, 320]
                }
            ]
        }
        // get bar chart canvas
        var income = document.getElementById("income").getContext("2d");
        // draw bar chart
        new Chart(income).Bar(barData);
    </script>
</body>

</html>
```

<br/>

    
                               The End of Part One

## 2. Canvas API..

        in this part we will discuss the following points

* What is Canvas API.
* Give example of implemntation.

<br/>

                           The beginning of Part One

### 2.1: what Canvas API is:

 to set up a canvas 2D context.

### 2.2: Example of implemntation:

```html
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />
    <script type="application/javascript">
        function draw() {
            var canvas = document.getElementById('canvas');
            if (canvas.getContext) {
                var ctx = canvas.getContext('2d');

                ctx.fillStyle = 'rgb(200, 0, 0)';
                ctx.fillRect(10, 10, 50, 50);

                ctx.fillStyle = 'rgba(0, 0, 200, 0.5)';
                ctx.fillRect(30, 30, 50, 50);
            }
        }
    </script>
</head>

<body onload="draw();">
    <canvas id="canvas" width="150" height="150"></canvas>
</body>

</html>
```

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
