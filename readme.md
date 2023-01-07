# W3C IIS logs analysis
## Introduction
This notebook analyzes IIS logs and generates a detailed report containing everything from total log file size, status codes breakdown, user agent interpretations to box plots of the response time.

Read more about the IIS [W3C Extended Log File Format](https://www.w3.org/TR/WD-logfile.html) [here](https://learn.microsoft.com/en-us/previous-versions/iis/6.0-sdk/ms525807(v=vs.90)).

## Logs 
You can use the testing log files provided in the `test_logs` folder or generate sample logs using my IIS log generator script [here](https://github.com/samuelskottenborg/W3C-IIS-logfile-generator).

## Usage
Simply set the path to the IIS log folder and run the notebook.