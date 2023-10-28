


<!doctype html>
<html>
<head>
  <title>DataVisualization</title>
  <meta charset="utf-8" />

  <script src="https://cdn.jsdelivr.net/npm/vega@5.25.0"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@5.16.0"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@6.22.2"></script>

  <style media="screen">
  .vega-actions a {
    margin-right: 5px;
  }
</style>
</head>
<body>
    <div class="header">
      <h1>ELL824: SELECTED TOPICS IN INFORMATION PROCESSING - II ( Data Visualization)</h1>
      <h2>Name: Pooja Singh (EEZ228470)</h2>
    </div>

  <div id="vis"></div>

  <script>
      var vlSpec = {
        $schema: 'https://vega.github.io/schema/vega-lite/v5.json',
        data: {"url":"https://raw.githubusercontent.com/poojascience/ELL824_DV/main/HW_Excel.csv"},

      vconcat: [
      
        {
            
            
                mark: {type: "arc", "tooltip": true},
                "width": 300,
                "height": 300,
                encoding: {
                  theta: {field: "Units", type: "quantitative",aggregate: "sum"},
                  color: {field: "Item", type: "nominal", "stack": true}
                }
          },
        {
          mark: {type: "bar", "color": "orange", legend: null, "tooltip": true},
          "width": 300,
          "height": 300,
          encoding: {
            y: {field: 'Total',  aggregate: 'sum'},
            x: { sort: "-y", field: 'Rep'}
            // "color": {"aggregate": "sum", "field": "Total"}
          }
        },
      {
        mark: {type: "point", "tooltip": true},
        "width": 300,
          "height": 300,

        encoding: {
          x: {field: "Units", type: "quantitative", title: "Units value"},
          y: {field: "UnitCost", type: "quantitative",title: "UnitCost value"},
          color: {field: "Item", type: "nominal",legend: null},
          fill: {scale: "color",field: "Item"}
        }

      },

      {
        mark: {
          type: "line", "tooltip": true
        },
        "width": 300,
          "height": 300,
        encoding: {
          "color": {"value": "red"},
          y: {field: "Total", type: "quantitative",aggregate: 'sum'},
          x: {field: "OrderDate",timeUnit: "month",type: "temporal", axis: {labelAngle: 30}},
        }
      },
      {
        layer: [
        {
          mark: {"type": "bar", "tooltip": true},
          "width": 300,
          "height": 300,
          encoding: {
            x: {
              bin: true,
              field: "Units"
            },
            y: {aggregate: "count",axis: {orient: "left", title: "Record-count"}}
          }

        },
        {
          mark: { "type":"rule", "color": "red", "tooltip": true},
          "width": 300,
          "height": 300,
          
          encoding: {
            y: {field: "Units", aggregate: "mean", axis: {orient: "right"} },
            size: {value: 2},

          }
        },
        

        ],
        resolve: {scale: {y: "independent"}}
      }

      ]
    };

      // Embed the visualization in the container with id `vis`
      vegaEmbed('#vis', vlSpec);
    </script>
  </body>
  </html>
