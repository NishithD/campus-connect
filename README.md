# CAMPUS Connect
![Campus-Saathi-logo](https://github.com/anuran-roy/hacknpitch/blob/main/home/static/home/ic_launcher.png "CAMPUS OWL : ALWAYS GUARDING THE CAMPUS 💯 🥇 👍🏻 ")
 

# Requirements
Any Windows/Linux 4.14+ kernel/MacOS with Python 3.8.10 or above.
```bash
sudo apt-get install python3 # for Debian & Ubuntu based Systems
sudo yum install python3-devel.x86_64 # for RPM bases Systems
sudo  pacman -S glib2-devel pacman -U python-3.8.10 # for Arch Systems
```
For Windows 10 ,Mac,Android Download from offical site of Python and run their respective binaries .
```bash
python # in Windows 11 Terminal for installing python
```
## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the Django App.

```bash
pip3 install requirements.txt
python3 manage.py runserver [specify port] #for Linux Systems
```
For Windows Environment 
```bash
pip install requirements.txt
python manage.py runserver [specify port] #for Linux Systems
```
Note:- Virtualenv needs to be configured and activated for production server. WSGL and other workers , Static_files aswell as Allowed_Hosts needs to be configured in settings.py for final deployment over the net.

## Usage

```python
Performing system checks...

System check identified no issues (0 silenced).
September 20, 2021 - 17:09:32
Django version 2.0, using settings 'ChatApp.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License
MIT License

Copyright (c) 2023 Team 12, DN&VM

