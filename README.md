# C3 Chart Editor :bar_chart:
This is a chart editor I made using good ol' vanilla JavaScript and [C3.js](https://c3js.org/), a chart library based off of D3.js. [Bootstrap 4](https://getbootstrap.com/) is used for simple styling and responsiveness. Finally, [Require.js](https://requirejs.org/) is used with a local server to run in the browser.

To use C3 Chart Editor, I have it hosted on Heroku here: https://c3-chart-editor.herokuapp.com/index.html 

In case the link is down or you prefer to download your own copy, you will need to set up a local server.

### How to Use
:small_blue_diamond: Simply fill out the chart form and watch the chart magic happen! You can select chart type, give your chart a title and subtitle, choose a color theme, as well as provide labels for each chart axis and watch all changes happen in the live preview. 

:small_blue_diamond: For entering in chart data, you will only see changes after you hit the submit button. You fill out the series table(s) with you data. Each series represents one data group, for example, a line, bar, etc. Each table series also needs to have a unique data label. You can leave this blank if you are lazy and want a unique data label automatically generated for you. If you forget and accidentally enter in the same label twice, don't worrry. My validation check should yell at you to fix this.

:small_blue_diamond: You can add/delete as many table series as you like. You can also add/delete as many rows as your like for each table series too (However, there will always be at minimum one table series and one row to prevent you from completely deleting the table series from the page!). Clicking on the Rows All buttons will add/delete a row to all table series at the end. If you wish to add/delete a row to just one table series or in-between rows, you can use the add/delete buttons inside the table series that is attached to each row.

:small_blue_diamond: C3.js uses an optional third axis in its charts, called the Y2 Axis. I added this feature in case you would like to generate chart with this axis. Use the Y2 Column buttons to add/remove this optional column. You will see the Y2 Axis immediately upon adding the column (or disappearing if deleting it). However, remember you will need to hit the submit button with Y2 values to see it take effect and generate a chart.

:small_blue_diamond: All data entered into the table series must be numerical values only. Again, if you forget to do this, my validation check should yell at you some more!

:small_blue_diamond: You can resubmit data as much as you like. If you would like for the form to return to its initial state, simply hit the reset button.

:small_blue_diamond: Finally, the code is heavily commented...For my own reference. Please feel free to remove!




