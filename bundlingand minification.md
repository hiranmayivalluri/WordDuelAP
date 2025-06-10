<html>
  <body>
    <table style="width: 100%;">
     <h1>Bundling vs Minification</h1>

          <table>
            <caption>Comparison Table</caption>
            <thead>
              <tr>
                <th>Feature</th>
                <th>Bundling</th>
                <th>Minification</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Combines files?</td>
                <td> Yes</td>
                <td> No</td>
              </tr>
              <tr>
                <td>Reduces size?</td>
                <td> Yes (by reducing HTTP requests)</td>
                <td> Yes (by reducing characters)</td>
              </tr>
              <tr>
                <td>Tools used</td>
                <td>Webpack, Rollup, Vite</td>
                <td>Terser, UglifyJS, CSSNano</td>
              </tr>
              <tr>
                <td>When used?</td>
                <td>During build step</td>
                <td>During build step</td>
              </tr>
            </tbody>
          </table>
  </body>
</html>
