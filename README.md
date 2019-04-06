# PowerShell

## Verb-Noun (DoSomething-ToSomething)

### Display the command history
- get-history 

### Get help
- get-help
- get-help ...
- i.e. get-help Remove-AzResource

- get-help ... -examples
- i.e. get-help Remove-AzResource -examples
- i.e. get-help Remove-AzResource -full
- i.e. get-help Remove-AzResource -online

- help
- i.e. help start-transcript

### Get the list of available commands
- get-command
- get-command -verb New
- get-command -name

### Create a record of all or part of a Windows PowerShell session to a text file
- start-transcript
- stop-transcript

### Get
- get-verb | out-file "Filename.txt"
- notepad filename.txt

- get-verb | export-csv "filename.csv"
- notepad filename.csv

### MS-DOS like commands
- del filename.txt
- del filename.csv
- dir
