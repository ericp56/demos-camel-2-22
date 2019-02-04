demos-camel-2-22
================
Learning and demonstrations of using Apache Camel.

Look under src/main/resources/META-INF/spring/contexts

**camel-context.xml**

contains the "include" to run a specific context.

**contexts/* **

contain demonstrations of using spring.  include one of these in the camel-context.xml definition.

**context/http-to-socket**

This is a demonstration of putting a web interface on top of a socket REPL-like interface.  This is implemented in XML, no Java.

**context/pollerLoggerContext.xml**

This is a demonstration of using camel to "ping" an HTTP endpoint and to log the results.  This is implemented in XML, no Java.
