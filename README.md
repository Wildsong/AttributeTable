# AttributeTable

This is a fork of the Esri AttributeTable.

The purpose of the fork is to add export to an open spreadsheet format, ODF.

## License

The code was released under [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0), (see manifest.json),
which allows for derivative works like this one.

## What's different

In my brief search I did not find any version of AttributeTable in
version control anywhere so I pulled the source from "ArcGISWebAppBuilder, 
Developer Edition", version 2.19.

After tagging the initial version as "initial", I added a "dev" branch
and I am adding support for export in ODF format.

The standard AttributeTable only allows export in CSV format.  The
problem with CSV format is that long strings of numbers are often used
as account numbers in GIS, and when you import a CSV into a
spreadsheet they are typically converted automatically to floating
point numbers.

By distributing an ODF file instead, any modern spreadsheet will read
the data correctly.

I chose ODF format instead of XLS because it's inherently open and
nothing needed reverse engineering or other license encumbrances.
(Also, I am a fan of LibreOffice. :-)

## Authors

This version: Brian Wilson <brian@wildsong.biz>

Original, from manifest.json: "Esri R&D Center Beijing",

