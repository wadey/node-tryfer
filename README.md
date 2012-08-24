# node-tryfer: A Node Zipkin Tracer Library

[![Build Status](https://secure.travis-ci.org/racker/node-tryfer.png?branch=master)](http://travis-ci.org/racker/node-tryfer)

Zipkin is a Distributed Tracing system, tryfer is a Python/Twisted client library for Zipkin, and node-tryfer is a port of tryfer

---

To see an example of tracing working in an http client and on an http server, run:

```
node examples/tracing_server.js
```

and

```
node examples/tracing_client.js GET http://localhost:8080/
```

in different terminals.
