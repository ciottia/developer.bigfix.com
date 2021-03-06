# type: application usage summary instance

The &lt;application usage summary instance&gt; inspectors return information about the multiple instances of specific applications.

# first start time of &lt;application usage summary instance&gt; : time

Returns the start time of the specified application instance since the computer was configured to track it, regardless of reboots.

# image path of &lt;application usage summary instance&gt; : string

Returns the full path to the executable file that represents the instance of the specified application.

**Note:** On AIX systems this inspector always returns the error *'expression refers to nonexistent object'* because the application path is not available on that platform.

# last start time of &lt;application usage summary instance&gt; : time

Returns the last time this specified application was started.

# last time seen of &lt;application usage summary instance&gt; : time

Returns the last time this specified application was seen running.

# name of &lt;application usage summary instance&gt; : string

Returns the name(s) of the application instance(s) currently enabled for usage summaries.

# size of &lt;application usage summary instance&gt; : integer

Returns the size of the specified application instance.

# string version of &lt;application usage summary instance&gt; : string

Returns the version of the specified application instance as a string value.

# total duration of &lt;application usage summary instance&gt; : time interval

Returns the total elapsed time that the specified application instance has been running.

# total run count of &lt;application usage summary instance&gt; : integer

Returns the number of times that the specified application instance has been run since the client was configured to track it.

# version of &lt;application usage summary instance&gt; : version

Returns the version of the specified application instance.
