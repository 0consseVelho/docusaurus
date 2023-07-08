```code // This function is used to send an opaque message to the Blink server // We need to set c_mongo to true to indicate that we are still in the Blink session // Otherwise, the client might pause the session if it does not receive any messages from us // However, this also means that we cannot pause the session ourselves, so we have to be careful // For example, we should only make RPC calls after waiting for 1~2 seconds to avoid blocking the session void SendOpaque1(TMessageHandler messageHandler, int64 bpo)    c_mongo = true; // flag to stay in the Blink session   c_messageHandler = messageHandler; // handler for the opaque message   =Peritus&link= // some code that I don't understand  ``` 
**Download File ↔ [https://t.co/YUku5AXtCy](https://t.co/YUku5AXtCy)**


 8cf37b1e13
 
