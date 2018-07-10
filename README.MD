## NetworkMonitor

#### Usage

```objectiveC
+ (instancetype)sharedInstance;

- (void)startMonitorWithInblock:(WXNetworkBlock)inBlock outBlock:(WXNetworkBlock)outBlock;
- (void)stopMonitor;
```

block will return 1 time per seconds, unit is bytes/s.
transform units according to you.


#### carthage 

```
github "supergithuber/NetworkMonitor" == 0.7.0
```