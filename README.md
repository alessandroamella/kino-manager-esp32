> [!IMPORTANT]
> This repository has moved to the [kino-manager monorepo](https://github.com/alessandroamella/kino-manager/tree/master/hardware/esp32) and is archived.
> Questo repository è stato spostato nel [monorepo kino-manager](https://github.com/alessandroamella/kino-manager/tree/master/hardware/esp32) ed è archiviato.

# Kino Manager ESP32

You just need to install the [LiquidCrystal_I2C](https://docs.arduino.cc/libraries/liquidcrystal-i2c/) library.

Communication is handled by the [frontend](https://cafe.kinocampus.it/cashier) via Web Serial API.

For quick access, data is simply sent as:

- `itemName|itemPrice|totalPrice` for items
- `paymentMethod|amount` for payments

The ESP32 will then display the data on the LCD screen.
Note that the `|` character is used as a separator.
