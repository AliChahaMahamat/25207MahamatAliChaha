1---What is Logging?
    Logging is an API that allows tracing and recording of errors and events within applications. 
    When an application generates a logging call, the Logger records the event in a LogRecord. 
    This LogRecord is then sent to corresponding handlers or appenders. 
    Before being output to a console or file, appenders format the log record using formatters or layouts.



2---Importance of Logging
    Logging is crucial for debugging, monitoring, and maintaining an application. 
    It provides insights into the application's performance, aids in identifying and diagnosing issues, and 
    is essential for auditing and compliance purposes. 
    Effective logging helps in:
      --Debugging and fixing bugs.
      --Monitoring the application's behavior and performance.
      --Maintaining a history of application events for auditing purposes.
      --Ensuring compliance with industry standards and regulations.


      
3---Log Levels
    Log levels control the detail and extent of log files generated.
    Each level has a numeric value, and there are seven basic log levels and two special ones. 
    By specifying the desired level of logging, you can filter the amount of detail captured in the logs. 
    The basic logging levels are:
Level	     Value	    Used for
SEVERE	   1000	      Indicates serious failures
WARNING	   900	      Potential problems
INFO	     800	      General informational messages
CONFIG	   700	      Configuration-related messages
FINE	     500	      General developer information
FINER	     400	      Detailed developer information
FINEST	   300	      Highly detailed developer info
