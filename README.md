# Presentation: Tracing a Memory Leak in a Long Running Eventmachine Application

In Huanteng Smart we manufacture smart household gadgets which all connect to a single long running eventmachine application to receive and send instructions with the server. This eventmachine application is a single Linux process holding all TCP connections never closes them. One day, we found that this process was leaking memory, and here is how we managed to trace its cause.

## For author

### Show

    rake

### Publish

    rake publish

## For viewers

### Install

    gem install rabbit-slide-pmq20-tracing-a-memory-leak-in-a-long-running-eventmachine-application-en

### Show

    rabbit rabbit-slide-pmq20-tracing-a-memory-leak-in-a-long-running-eventmachine-application-en.gem

