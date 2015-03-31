#Summary

This is a simple ruby client which can be used to send metrics to a statsd server running locally on port 8125.
The client reads the standard input or any file passed in as an argument for statsd commands. The
valid commands are:

timing <name> <value>
increment <name>
decrement <name>
gauge <name> <value>
count <name> <value> [sample_rate]