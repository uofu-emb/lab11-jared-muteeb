# Lab 11 Bluetooth

**Authors**: Jared & Muteeb

## Activity - advertising

- Changed the BLUETOOTH_DATA_TYPE_COMPLETE_LOCAL_NAME to 'Muteeb BLE'.
- Serial port prints:

```
BTstack counter 0001
BTstack up and running on 28:CD:C1:0F:20:C7.
```

**Muteeb BLE Advertising**

![Muteeb BLE Advertising](./imgs/lab11-bluetooth-activity-adversting.png)

## Activity - attributes, services, and characteristics.

### Task 1

| ![Muteeb BLE Services](./imgs/lab11-bluetooth-activity-services-1.png) | ![Muteeb BLE Battery Service Properties](./imgs/lab11-bluetooth-activity-services-2.png) |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Muteeb BLE Services                                                    | Muteeb BLE Battery Service Properties                                                    |

### Task 2

| ![Muteeb BLE Gatt Services Name Change](./imgs/lab11-bluetooth-activity-services-3.png) |
| --------------------------------------------------------------------------------------- |
| Muteeb BLE Gatt Services Name Change                                                    |

### Task 3

| ![The characteristic has type GAP_DEVICE_NAME, is read only, and includes a literal string value.](./imgs/lab11-bluetooth-activity-services-4.jpeg) |
| --------------------------------------------------------------------------------------------------------------------------------------------------- |
| The characteristic has type GAP_DEVICE_NAME, is read only, and includes a literal string value.                                                     |

## Activity 3 - HCI packet handling

Improved our debugging by logging whenever a client connects to our device.

![Muteeb BLE Logging](./imgs/lab11-bluetooth-activity-logging.png)

## Activity 4 - add a service

Temperature Service

![Muteeb BLE Temperature Service](./imgs/lab11-bluetooth-activity-temperature.png)
