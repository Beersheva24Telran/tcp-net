# HW 47 Definition
## Implementation of Graceful Shutdown
### Make possible running request to be finished but if the shutdown action has been performed new requests will be skipped out
### Hints:
setSoTimeout with small timeout<br>
Handler of SocketTimeoutException will check out whether the shutdown method of server has been called. If so the connection should be closed <br>
### Testing
 running TcpServer thread (multithreading) <br>
 scanning input console for running shutdown command
## Implementation of DoS attacks prevention
### Applying Fixed Thread Pool executor service
### Closing IDLE connections after pre-configured TIMEOUT
### If there are many (pre-configured number) responses in the line with ResponseCode not OK the session should be closed 
### If there are many requests per second (preconfigured number) the session should be closed

