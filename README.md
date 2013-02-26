# nagios_report_grabber
Grab predefined reports via html get using bash

## Usage
Simply execute the script `grabreports`

Reports are placed in the home directory of the user that executed it

## Requirements
Calls upon the `htmldoc` command.  This can be found here: http://www.htmldoc.org/

Place the following env vars in file: .nagios_report_grabber.env
   export NAGIOS_SERVER="server.domain"
   export NAGIOS_USERNAME="username"
   export NAGIOS_PASSWORD="pasword"
