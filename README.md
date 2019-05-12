# MiBand3
Library to work with Xiaomi MiBand 3

Library based on Yojesh Ojha's library:-
https://github.com/yogeshojha/MiBand3
https://medium.com/@yogeshojha/i-hacked-xiaomi-miband-3-and-here-is-how-i-did-it-43d68c272391

# Run

### Install dependencies

`pip install -r requirements.txt`

Turn on your Bluetooth

Unpair you MiBand2 from current mobile apps

Find out your MiBand3 MAC address

```sudo hcitool lescan```

Run this to auth device

```python main.py MAC_ADDRESS --init```

If you having problems(BLE can glitch sometimes)

```sudo hciconfig hci0 reset```
