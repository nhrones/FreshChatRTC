# Fresh Chat RTC

A `fresh` chat app that leverages deploy `BroadcastChannel`    
as a signal server used to connect two peers over a WebRTC-Datachannel.

[![comms](./comms.png)](https://rtc-dice-app-server.deno.dev/)    
 

### Usage

To start the application:

```
deno task start
```

After adding, removing, or moving a page in the `routes` directory,     
or adding, removing, or moving an island in the `islands` directory,     
run:

```
fresh manifest
```
Run it ... https://fresh-chat-rtc.deno.dev/