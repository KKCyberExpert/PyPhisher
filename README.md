                                     ------------------------------------> PyPhisher Phishing---------------------------<
       
       [√] Description :
Ultimate phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.



[+] Installation

Install dependencies (git, python, php ssh)

For Debian (Ubuntu, Kali-Linux, Parrot)

----->  sudo apt install git python3 python3-pip php openssh-client -y

For Arch (Manjaro)
----->  sudo pacman -S git python3 python-pip php openssh --noconfirm

For Redhat(Fedora)
----->  sudo dnf install git python3 php openssh -y

For Termux
----->   pkg install git python3 python-pip php openssh -y

Clone this repository
git clone https://github.com/KKCyberExpert/PyPhisher

Enter the directory
cd PyPhisher

Install all modules
pip3 install -r files/requirements.txt --break-system-packages

Run the tool

python3 pyphisher.py

Pip
pip3 install pyphisher [For Termux]
sudo pip3 install pyphisher  --break-system-packages [For Linux]
pyphisher

Docker
sudo docker pull kasroudra/pyphisher
sudo docker run --rm -it kasroudra/pyphisher


Support
OS	Support Level
Linux	Excellent
Android	Excellent
iPhone	Alpha (Recommended docker)
MacOS	Alpha (Recommended docker)
Windows	Unsupported (Use docker/virtual-box/vmware)
BSD	Never tested


Options:-

usage: pyphisher.py [-h] [-p PORT] [-o OPTION] [-t TUNNELER]
                    [-r REGION] [-s SUBDOMAIN] [-u URL] [-m MODE]
                    [-e TROUBLESHOOT] [--nokey] [--noupdate]

options:
  -h, --help                     show this help message and exit
  -p PORT,             --port PORT  PyPhisher's server port [Default : 8080]
  -o OPTION, --option OPTION
                        PyPhisher's template index [Default : null]
  -t TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening
                        [Default : Cloudflared]
  -r REGION, --region REGION
                        Region for loclx [Default: auto]
  -s SUBDOMAIN, --subdomain SUBDOMAIN
                        Subdomain for loclx [Pro Account]
                        (Default: null)
  -u URL, --url URL     Redirection url after data capture [Default :
                        null]
  -m MODE, --mode MODE  Mode of PyPhisher [Default: normal]
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler [Default: null]
  --nokey               Use localtunnel without ssh key [Default:
                        False]
  --noupdate            Skip update checking [Default : False]





Features:

1.) Multi platform (Supports most linux)
2.) Easy to use
3.) Possible error diagnoser
4) 77 Website templates
5) Concurrent 4 tunneling (Cloudflared, Loclx and LocalHostRun, Serveo)
6) Upto 8 links for phishing
7) OTP Support
8) Argument support
9) Credentials mailing
10) Built-in masking of URL
11) Custom masking of URL
12) URL Shadowing
13) Redirection URL settings
14) Portable file (Can be run from any directory)
15) Get IP Address and many other details along with login credentials




Requirements

> Python(3)
 > requests
  >rich
  > beautifulsoup4
 > PHP
   > SSH
      >900MB storage
         > If not found, php and python modoules will be installed on first run

Tested on:-

 > Termux
> Ubuntu
> Kali-Linux
> Arch
> Fedora
> Manjaro


Usage

Run the script
Choose a Website
Wait sometimes for setting up all
Send the generated link to victim
Wait for victim login. As soon as he/she logs in, credentials will be captured
>>>>>>Boooooooom>>>>>


![DESCLAIMER]

This tool is developed for educational purposes. 
Here it demonstrates how phishing works. 
If anybody wants to gain unauthorized access to someones social media, he/she may try out this at his/her own risk.
You have your own responsibilities and you are liable to any damage or violation of laws by this tool. 
The author is not responsible for any misuse of PyPhisher!
