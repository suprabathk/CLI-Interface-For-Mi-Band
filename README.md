# Mi Band 3
Library to work with Xiaomi Mi Band 3

Library based on Yojesh Ojha's library:-
https://github.com/yogeshojha/MiBand3
https://medium.com/@yogeshojha/i-hacked-xiaomi-miband-3-and-here-is-how-i-did-it-43d68c272391

Yojesh Ojha's library is amazing. But there are quite a few bugs and the libraries are out-dated.
So, I fixed the bugs and made some minor changes.

The Heart rate feature seems to glitchy even after some fixes. (I am working on it!)
Please report any bugs.

# Run

### Install dependencies

`sudo pip install -r requirements.txt`

Turn on your Bluetooth

Find out your Mi Band 3 MAC address

```sudo hcitool lescan```

Run this to auth device

```python main.py MAC_ADDRESS --init```

If you having problems(BLE can glitch sometimes)

```sudo hciconfig hci0 reset```
