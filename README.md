# converto
An all in one web app designed to convert csv files into a portable web code section to be added to web pages.

Currently built for KS document schedules, but can be easily modded for other, similar conversions.
Set up to accept local upload of three csv files. Outputs html with individual csv entries set up in divs as a pseudo-table. The outputted html includes a simple javascript filter with search box built into the html. The rows and columns have consistent classes to make it easy to manipulate them with css. New css can be added externally, or added by changing the contents of the style area near the beginning of the contents of the "firstpart" var (holds a template literal).

The html produced can be dropped right into a web page in a wcms. The css and js is completely self-contained as internal.

Licensed under Creative Commons non-commercial share alike open source license
