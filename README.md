## Installation
#### Installing Python3
- For Windows: [Download Python 3.12.2](https://www.python.org/ftp/python/3.12.2/python-3.12.2-amd64.exe)
- For Linux distributions: [Instructions for Installing Latest Python Version](https://dev.to/ivayloiv/install-latest-python-version-on-any-linux-distro-5gc3)

#### Installing Python3 Modules
- Install the required modules from `requirements.txt` using the following command:
```bash
pip install -r requirements.txt
```

### Registration Grass Account : [Sign Up Here](https://app.getgrass.io/register?referralCode=gUus7rmtotluawp)

## How to Use
#### Obtaining Your Grass User ID
- Log in to [Grass](https://app.getgrass.io).
- Press F12 to open the console, then type `allow pasting` and press enter.
- Paste the following code into the console:
```javascript
localStorage.getItem('userId')
```

#### Usage Instructions
- Open the file named `proxy_list.txt` and insert your proxies.
- Run `python run.py` and input your user ID when prompted.

- For multiple accounts, each with its own proxy:
  - Insert your account user IDs into `user_id.txt` and your proxies into `proxy_list(all).txt`.
  - Then run `python foreachuser_id_proxy.py`.
