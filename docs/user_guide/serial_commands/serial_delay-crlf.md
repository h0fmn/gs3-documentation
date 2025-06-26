# `serial delay-crlf <0000>`

## Description
Configures the transmit delay, which can be from `0` to `86,400,000`.

## Example
```
[admin@ssh-to-serial]>serial delay-crlf 300
UART Config - Base: 0x4000D000
 Clock: 120000000 Hz
 Baud: 9600
 Data Size: 5
 Parity: N
 Stop Bits: 1
 Flow Control: N
 Transmit Delay: 300 ms
Transmit delay set to 300 milliseconds.
```