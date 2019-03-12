# About

The project combines all dependencies needed to use a single to get tracing functionality 

Based on:

* https://github.com/opentracing-contrib/java-specialagent
* https://github.com/collectivesense/logsense-opentracing

# How to use?

1. Download https://github.com/collectivesense/logsense-opentracing-agent/releases/download/v1.0.0/logsense-opentracing-agent-1.0.0.jar
2. Run Java VM with `-javaagent:logsense-opentracing-agent-1.0.0.jar -Dlogsense.token=CUSTOMER_TOKEN`, replacing `CUSTOMER_TOKEN` with the actual value

### Other options

You can also specify custom hostname and port, using `-Dlogsense.host=<HOSTNAME> -Dlogsense.port=<PORT>`. The variables can be also provided via environment
