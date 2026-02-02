# FB Auto Forget Tool (Termux)

FB Auto Forget Tool is a Python-based automation tool designed to run on Termux.  
It helps perform Facebook forget actions in an automated way.

## Features

- Runs on Android using Termux
- Lightweight and fast
- Simple setup
- Uses updated Python libraries

## System Requirements

- Android device
- Termux (latest version)
- Python 3
- Stable internet connection

## First Time Setup

Update packages and install dependencies:

pkg update  
pkg upgrade  
pkg install git  
pkg install python  
pip install requests  
pip install mechanize  
pip install bs4  
pip install stdiomask  
pip install httpx  
pip install idna  
pip install pycurl  
pip install certifi  
pip install aiohttp  
pip install fake_useragent  
cd
clear

Allow storage permission:

termux-setup-storage  

## Installation

Clone the repository and run the tool:

cd 
rm -rf AutoForget
git clone --depth=1 https://github.com/Saiyadul123/FB-AutoForget.git  
cd FB-AutoForget  
git pull  
chmod 777 forget  
python run.py  

## Troubleshooting

- If a module is missing, install it manually using pip  
- Make sure Python is properly installed  
- Use a fresh Termux session if errors persist  

## Disclaimer

This tool is for educational purposes only.  
The developer is not responsible for misuse or account issues.

## Author

Saiyadul  
GitHub: https://github.com/Saiyadul123
