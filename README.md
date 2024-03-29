eiseXLSX
========

Simple XLSX file data read-write library

This class was designed for server-side manipulations with uploaded spreadsheets in Microsoft® Excel™ 2007-2011-2013 file format – OpenXML SpereadsheetML.

Current version of this library allows to read user-uploaded file contents and to write data to preliminary uploaded template file and send it back to the user:
- it allows to change existing cell data
- clone rows and fill-in new rows with data
- clone sheets within workbook, remove unnecessary sheets
- colorization of cells.

This library offers an easiest way to make Excel™-based EDI with PHP-based information systems, for data input and output.

Users are no longer need to convert Excel™ spreadsheets to CSV and other formats, they can simply upload data to the website using their worksheets.

You can use files received from users as your website’s output document templates with 100% match of cell formats, sheet layout, design, etc. With eiseXLSX you can stop wasting your time working on output documents layout – you can just ask your customer staff to prepare documents they’d like to see in XLSX format. Then you can put these files to the server and fill them with necessary data using PHP.

Unlike other PHP libraries for XLSX files manipulation eiseXLSX is simple, compact and laconic. You don’t need to learn XLSX file format to operate with it. Just use only cell addresses in any formats (A1 and R1C1 are supported) and data from your website database. As simple as that.
