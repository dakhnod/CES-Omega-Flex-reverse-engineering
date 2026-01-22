The communication between the gateways and the locks themselves is somehow encrypted.

If your Suite software shows some unfinished transfer jobs, you will be able to find them in the SYSTEM database, as described in [the doc](DATABASE.md).

After glancing over the data briefly, it looked quite random, other than
- a 0x20 at the beginning
- some 0xFFs somewhere near the end (can appear multiple times)
- the _random_ portion somehow only consisting of small numbers

I also notices that the packets with the same data but designated for different nodes seem to be identical, indicating the same encryption keys for all locks in one system.
