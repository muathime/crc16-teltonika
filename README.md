# crc16-teltonika
Inspired by a StackOverflow answer here
# Install
npm i @muathime/crc16-teltonika

# Example
//generate 4-byte CRC-16 checksum

const crc16 = require("crc16-teltonika").crc16teltonika;

const generated_cr16 = crc16(
  Buffer.from("0C010500000007676574696E666F01", "hex")
).toString(16);

console.log(generated_cr16);
