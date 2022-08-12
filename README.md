# Web Security Scanner &amp; Exploitation.

```bash

Web Security Scanner


              ,~,
             ((()-                   - GSec v0.6
             -''-.                   - by c0deninja 
            (\  /\)                  - @gotr00t0day (Instagram)
      ~______\) | `\
   ~~~(         |  ')                Happy Hacking!!!
      | )____(  |                    
     /|/     ` /|
     \ \      / |
     |\|\   /| |\
```
![Python Version](https://img.shields.io/badge/python-3.9.12-green)
![Issues](https://img.shields.io/github/issues/gotr00t0day/Gsec)
![Stars](https://img.shields.io/github/stars/gotr00t0day/Gsec)

## 🛠️ Installation

```bash

git clone https://github.com/gotr00t0day/Gsec.git

cd Gsec

pip3 install -r requirements.txt

# Make sure that nuclei-templates is cloned in the / directory. Gsec fetches the templates from ~/nuclei-templates
python3 install.py

```

## Usage

```bash
# normal (passive and aggresive scans)

python3 gsec.py -t https://domain.com

# Passive Recon

python3 gsec.py -t https://domain.com --passive_recon

```
