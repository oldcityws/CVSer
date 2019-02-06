# CVSer
View, export, and process CVS file data.

*** Commas in CVS data cause extra columns to show up and will screw up the data - stripping out commas via opening in M$ Excel and then searching for commas to replace or strip out is necessary to the proper function of this app until comma analysis is implemented. ***

*** Currently apostrophes are screened-for and are replaced with underscores to avoid causing errors when the SQLite recordset commands are used.

This is Version One of this app; 

ROADMAP
1.  Implement Prepared Statements so that weird characters don't kill the function / import of data.
2.  Implement intelligent comma handling to allow users to declare which data pieces are inclusive of commas.
3.  Implement MySQL export of data

###
