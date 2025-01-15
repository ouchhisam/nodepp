
### TERMUX
- For Termux Android [Download Here](https://f-droid.org/repo/com.termux_1020.apk) [F-Droid Version] and Allow Permission Storage On Setting Termux
- Install Python3 and Git:
```bash
pkg update; pkg upgrade -y; pkg install git python python-pip -y
```
- Download this script using Git:
```bash
git clone https://github.com/zainarain279/Nodepay.git
```
```bash
cd Nodepay
```

```bash
cp libcurl-impersonate-chrome.so.4 /data/data/com.termux/files/usr/lib
```
- Installing requirements: 
```bash
python -m pip install -r requirements.txt
```
# Run the Script
- Replace the proxies example in ```proxies.txt``` to your own proxies, please use only 3 proxies with proxies. If you run multiple accounts make sure you have 3 proxies for each accounts.
- For multi accounts, insert your tokens perlines in file ``tokens.txt``

```bash
python run2.py
```
