# Tardy Logger
Tardy Logger is a desktop application for automating the creation of target passes for the Farrell B. Howell ECE-8 school.
![image](https://user-images.githubusercontent.com/1467409/165204006-7c8c3551-ee73-4e2c-b357-6c29140dc13e.png)

It allows for quickly searching and printing Hall Passes on a thermal printer. In addition, it pushes log records to google sheets for updating records or analytics on tardy frequencies.

For a full list of features and configuration instructions see the README on the repository.
<a href="https://github.com/hockeytim11/TardyLogger/blob/main/README.md" title="Tardy Logger README">README</a>

## Code Repository
https://github.com/hockeytim11/TardyLogger

## Privacy Policy
Tardy Logger uses google sheets to pull the Student data into memory for searching and printing passes. In addition,
it will append a row to a google sheet specified in the app config (TardyLogger.exe.config). This application does not 
collect any data from users. All data access is only used for feature support in the application and no data is collected 
by the developer of this application. 

The application will promt you for access on first launch and saves the refresh token locally. The only connections made are 
from the local application directly to googles servers. The permissions needed for the features grant access to all of your
google sheets, but the application will only ever interact with the configured in the application configuration file.
