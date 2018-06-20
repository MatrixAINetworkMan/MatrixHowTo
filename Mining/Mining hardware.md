### Q1. What hardware do you think will be required in September and December to run a node capable of 1000 tps?

We’re currently using DELL R730 as test nodes, which meets the 1,000 TPS requirement. You can achieve substantial TPS gains by clustering.
 
We’re using a VU7P + ZU 21 DR FPGA prototype chip. The ZU 21 DR component is composed of ARM Cortex A53 superscaler processors. This supports a "two miners and a verifier" mode. And this setup has reached 50K TPS.
