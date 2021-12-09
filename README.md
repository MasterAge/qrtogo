# QRToGo
A library for processing ASCII representations of QR Codes.

This is intended to be used for CTFs, but may be used by anyone.

## Setup
```bash
git clone git@github.com:MasterAge/qrtogo.git
cd qrtogo
pip install -r requirements.txt qrtogo
```

## Usage
```bash
python qrtogo.py  -h
usage: QRToGo [-h] -w WIDTH [-b BLACK] [-v] [--dump-qr-code] file

Processes ASCII QR Codes.

positional arguments:
  file                  A file containing an ASCII QR code.

optional arguments:
  -h, --help            show this help message and exit
  -w WIDTH, --width WIDTH
                        The width of the QR code, including the whitespace.
  -b BLACK, --black BLACK
                        The character that represents the black squares
  -v, --verbose         Enable verbose logging.
  --dump-qr-code        Write the created QR code image to disc.
```