Here are the functions you can use in Python.

To import the module:
`import spi`

To initialize the SPI with default parameters (8 bits, 500KHz):
`spi.initialize()`

To initialize the SPI with special parameters:
`spi.initialize(mode, bytesPerMessage, speed, delay)`

To transfer:
`spi.transfer((int,int,int,int....))`

If you are initialized for 8 bytes and input a 3 byte array, the function will fill out the rest of the transfer with 0's.

To close the SPI port:
`spi.end()`