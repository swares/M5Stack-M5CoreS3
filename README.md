# M5Stack-M5CoreS3
Fixed example sketches for M5Stack M5CoreS3



Notes:

Library Changes:
- Use M5Unified, or M5CoreS3, instead of M5core or M5Core2

I2C Busses  
i2cBus_t i2cBus_Internal    = {&Wire, GPIO_NUM_12, GPIO_NUM_11};  
i2cBus_t i2cBus_Groove_Port = {&Wire, GPIO_NUM_2, GPIO_NUM_1};  

Changes Made:
- Use M5Unified, or M5CoreS3, instead of M5core or M5Core2
- auto cfg = M5.config();
- May or may not need to add Wifi or Wire libraries

See: Points for porting to M5Unified
