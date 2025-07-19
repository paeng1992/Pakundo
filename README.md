for android "Termux" 
pkg install git -y
pkg install python -y
cd
rm -rf Pakundo
git clone https://github.com/paeng1992/Pakundo.git
cd Pakundo
pip install -r requirements.txt
python Pakundo.py


for ios "iSH"
apk add git
apk add python3
apk add py3-pip
cd
rm -rf Pakundo
git clone https://github.com/paeng1992/Pakundo.git
cd Pakundo
pip install -r requirements.txt
python3 k.py
