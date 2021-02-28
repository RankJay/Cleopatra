# **Cleopatra**

**Account :** https://twitter.com/Cleopat51842118

## Set up notes

### How to install Tweepy

First, check your Python version with ``python3 --version`` or ``python --version`` on console (terminal/shell/command prompt).

#### If you have Python 3.6 or greater, you can just run:

1. Install Tweepy

```
pip3 install tweepy
```

2. [Install Brownie](https://eth-brownie.readthedocs.io/en/stable/install.html), if you haven't already. Here is a simple way to install brownie.

```
pip install eth-brownie
```

3. [Install ganache-cli](https://www.npmjs.com/package/ganache-cli)

```
npm install -g ganache-cli
```


---

## Files
- **my_twitter_bot.py** - This is the main file that includes all the logic.
- **last_seen_id.txt** - This will contain the ID of the tweet that my_twitter_bot.py has seen last. If you see any errors when running the main file, try replacing the content with the ID of one of the tweets you want to examine.
- **keys_format.py** - Twitter API Keys


## Deployment
**Matic Mumbai Testnet Contract Address:**

1. Latest PriceFeed : 0xA057ad5604f90579764a340f70Ebd8109Dcb7e2C
2. ChainLink VRF : 0x6438762ab34186EcE4fc7C16B50cC3D58EE08080