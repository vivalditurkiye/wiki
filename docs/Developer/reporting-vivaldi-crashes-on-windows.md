Reporting crashes on Windows
Following a crash, a crash log (“.dmp” file) is created. Currently these are only created on Windows. Crash logs are not sent back to us automatically. You can however create a bug report and forward us a copy of the crash log manually, should you wish to assist us in fixing the issues. Such logs are greatly appreciated, as they provide information about where in the code things went wrong.

What is a crash?
There are two major types or crashes:

Full browser: Vivaldi shuts down unexpectedly
Per site: a “dead bird” is shown rather than the content of the website
Any other unexpected behaviour, such as situations where Vivaldi becomes unresponsive for prolonged periods (or indefinately) are not “crashes” and no crash log will be created.

Finding the crash logs
To open the folder containing Vivaldi crash logs, do the following:

Open the “Run” dialog ([Windows Key]+R)
Paste the following text and press “OK“:
"%userprofile%\appdata\local\vivaldi\user data\crashpad\reports"
An alternative, which is especially useful when you’re using a [Standalone version of Vivaldi](https://help.vivaldi.com/article/standalone-version-of-vivaldi/), is to follow the Profile Path on vivaldi://about to the User Data folder, where you can find the folder Crashpad with the reports.

To find the most recent crash, sort the folder by “Date modified”.

Reporting a crash
Open the [bug report page](https://vivaldi.com/bugreport/) and provide any details you feel may be associated with the crash (e.g. the website you were viewing). To send us a crashlog, you must enter a valid email address.

Shortly after sumbmitting your bug report, you should receive an email from us confirming that it has been logged. Reply to this email with the crash log(s) attached. It is recommended that you zip them up first, if you are able to do so.
