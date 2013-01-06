Here are the functions you can use in Python.

To import the module:
`import spi`

To initialize the SPI with default parameters (8 bits, 500MHz):
`spi.initialize()`

To initialize the SPI with special parameters:
`spi.initialize(mode, bitsPerMessage, speed, delay)`

To transfer:
'spi.transfer((int,int,int,int....))'
If you are initialized for8 bytes and input a 3 byte array, it will fill out the rest of the transfer with 0's.

To close the SPI port:
`spi.end()`
