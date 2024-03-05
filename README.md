This is a notebook to implement crime series time analysis based on examples in Steven Gottlieb's book.
It will take a CSV or excel file with three columns 
Event, FromDate, ToDate
Event: the report number or other identifier for the crime
FromDate: the earliest possible datetime that the event occurred
ToDate: the latest possible time that the event could have occurred
If only one date is supplied it can be in either date colum this will be adjusted during processing.
Any data outside the first three columns will be dropped.
will produce all charts and reports for the different time analysis in the book.
