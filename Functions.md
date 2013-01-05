Here are the functions you can use in Python.

To import the module:
`import spi`

To initialize the SPI with default parameters (8 bits, 500MHz):
`spi.initialize()`

To initialize the SPI with special parameters:
`spi.initialize(mode, bitsPerMessage, speed, delay)`

To close the SPI port:
`spi.end()`
