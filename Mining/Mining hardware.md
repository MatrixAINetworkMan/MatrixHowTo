### Q1. What hardware do you think will be required in September and December to run a node capable of 1000 tps?

A mining node requires a deposit of 10K MANs and processing power to run 1,000 TPS., which are necessary to support RPC service.

We’re currently using DELL R730 as test nodes, which meets the 1,000 TPS requirement. You can also achieve substantial additional TPS gains by clustering.

We’re using a VU 7P + ZU 21 DR FPGA prototype chip. 

The ZU 21 DR is composed of: 4 ARM Cortex A53  superscaler processors. 

This supports "two miners and a validator" node and this setup has reached 50K TPS.




#### Q2. Does the following HW configuration meet the requirements of MAN mining?

![](https://i.imgur.com/vsOTjNn.png)

You could say this configuration meets entry-level mining requirements, but since it only supports a single quad-core processor, the setup might not be sufficiently optimized to reach the desired TPS. 

In the Miner that MATRIX designed:

- One core is dedicated to network processing 

(Note: 1,000 TPS suggests a respective traffic of over 20Mbp)

- Another core is dedicated to remote procedure calls (RPC)

(This provides a shared web server, managing block data, and proving data to other nodes when requested.) 

- One core is for encryption and decryption, as well as validation 

(current standards supports 3,000 - 7,000 operations per second, but we’re focused on solving peak requirements, not just average one)
 
- Another core will be used to process transactions, (including removing duplicate transactions), 
move memory, as well as handle compression and decompression.

- After all of these processes are covered
the remaining cores will be used for PoW computing. 

We also need to factor in additional processing power for 
computing AI applications as well as providing services to other nodes and external users
This will generate extra rewards.

In terms of mining this would be an entry-level machine.