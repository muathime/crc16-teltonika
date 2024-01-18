# crc16-teltonika
Calculates the CRC16 hash of a given buffer.
Inspired by a StackOverflow answer [here](https://stackoverflow.com/questions/10564491/function-to-calculate-a-crc16-checksum)

# Install
npm i @muathime/crc16-teltonika

# Example
```
//generate 4-byte CRC-16 checksum

const crc16 = require("crc16-teltonika").crc16teltonika;

const generated_cr16 = crc16(
  Buffer.from("0C010500000007676574696E666F01", "hex")
).toString(16);

console.log(generated_cr16);
```
