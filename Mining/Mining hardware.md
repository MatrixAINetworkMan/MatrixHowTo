### Q1. What hardware do you think will be required in September and December to run a node capable of 1000 tps?

A mining node requires a deposit of 10K MANs and processing power to run 1,000 TPS., which are necessary to support RPC service.

We’re currently using DELL R730 as test nodes, which meets the 1,000 TPS requirement. You can also achieve substantial additional TPS gains by clustering.

We’re using a VU 7P + ZU 21 DR FPGA prototype chip. 

The ZU 21 DR is composed of: 4 ARM Cortex A53  superscaler processors. 

This supports "two miners and a validator" node and this setup has reached 50K TPS.