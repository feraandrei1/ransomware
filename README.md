## Ransomware

This is a basic ransomware that you can use to encrypt data from your computer

## Installation

Download or git clone this repository :

```bash
git clone https://github.com/feraandrei1/ransomware
```

(If you downloaded it unzip it)

You need to open the folder with VS Code. After that you can install the requirements by typing the terminal :

```bash
pip install -r requirements.txt
```

## How to use

To encrypt the files from the folder "test_folder" type in the terminal :

```bash
python ransomware.py -e test_folder -s 32
```

And choose a password.

This will encrypt all the files from the folder "test_folder" and create a random salt.

To decrypt it back type in the terminal :

```bash
python ransomware.py -d test_folder
```

Type the password

## Info

Info : You can connect your Outlook on the phone and get all the keys typed on your computer on your phone.

Resources : x4nth055

Please note, this repo is for educational purposes only. Use it just on your computer.
