pkg update

pkg upgrade -y

pkg install git

pkg install python -y

git clone https://github.com/CPMElsedev/CPMElsedev.git

cd CPMElsedev

git pull

pip install -r requirements.txt

python main.py
