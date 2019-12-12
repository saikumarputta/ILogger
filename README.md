# ILogger
logging,ILogger,ILoggerFactory

ILogger interface is to write log message of a given log level and create logging scopes. 
The interface itself have generic log methods or extension methods:

//logging levels

_logger.LogTrace();

_logger.LogDebug();

_logger.LogInformation();

_logger.LogWarning();

_logger.LogError();

_logger.LogCritical();

To catch more performance stuff we can use SeriLog third party service.
