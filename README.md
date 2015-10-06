#kinesis-web-reader

###About
Handy util for streaming AWS Kinesis records into your browser. Uses jQuery mobile to work on your phone.

###Dependencies
[AWS JavaScript API](https://aws.amazon.com/sdk-for-browser/)

[jQuery mobile](http://jquerymobile.com/)

###Notes
Modify `keepRecordCount` to control number of records retained during operation. Modify `recordPollInterval` for empty stream poll interval.

On Chrome, if the html file is loaded as a local file (versus served from a web server) use the `--allow-access-from-files` switch when starting per http://www.chrome-allow-file-access-from-file.com/.

