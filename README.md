To generate json cucumber reports its easy, you just execute the testray and it will generate it automatically under Reports/logs/.

If you want to get an HTML report you can then convert that json report into html with this tool for example:

    npm install cucumber-html-reporter --save-dev 
Then after running a case you will be able to generate a report using:

    node index.js path/to/json_report.json