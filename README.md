# Raven XML importer service

## Installation

Run with administrator privileges.

## Configuration

Change params in `appsettings.json` file of the installed application folder.

### Parameters

- RefreshCycleMinutes: how often will service check for new XML files
- WorkDir: where to look for XML files
- ProcessedDir: where to store processed files
- ErrorDir: where to store files that failed processing
- TableColumns: name of columns to store XML data to (XML name -> column name)
- ConnectionStrings: PGSQL database connection parameters

### Logging

Check EventViewer for `RavenService` logs.
