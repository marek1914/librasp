nRF24L01 transceiver examples
-----------------------------

Look for `GPIO_CE` and `SPI_CS` defines in the sources to find where CE GPIO
pin shall be connected: `GPIO_CE`, and transceiver's SPI slave number: `SPI_CS`.

* `nrf_rx`:
    nRF24 RX example (possible polling via nRF IRQ pin).

* `nrf_tx`:
    nRF24 TX example.

* `nrf_scan`:
    Simple 2.4GHz channels scanning example.

* `nrf_tx_car`:
    Transmit a carrier on a given channel. The transmission may be observed via
    `nrf_scan` example.
