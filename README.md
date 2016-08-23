JMeter
======

JMeter - WebSocket Sampler

Based on the work of Maciej Zaleski. 
Original here: the [Wiki pages](https://github.com/maciejzaleski/JMeter-WebSocketSampler/wiki) for instructions on how to install the plug-in.

============================================
Adaptation by Ray Oei

1.0.4
- Fix receiving response 
- Incorporated fixes by [elyrank]
- Removed log information from sampleResults as it corrupts jtl

Bumped to 1.0.3
- Bumped to Jmeter "2.13" support
- Bumped to Jetty "9.3.8" support
- Bumped to jUnit "4.12" support

Dependencies:
- jetty-io-9.3.8.v20160314
- jetty-util-9.3.8.v20160314
- websocket-api-9.3.8.v20160314
- websocket-client-9.3.8.v20160314
- websocket-common-9.3.8.v20160314