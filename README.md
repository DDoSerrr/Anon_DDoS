# Anon_DDoS
DDoS攻撃を行うための強力なツール(多分これが最強)<br>

## 対応OS
* Debian
* FreeBSD
* Windows10 ~

## インストール方法
**Debian** <br>
以下のコマンドを入力するとインストールが出来ます。
```
sudo apt update && sudo apt upgrade -y
sudo apt install python3-pip git
sudo pip3 install socks
git clone https://github.com/ware255/Anon_DDoS.git
cd Anon_DDoS
python3 anon_ddos.py
```

**FreeBSD** <br>
物凄く恐縮ですがFreeBSDを使ったことないので間違ってるかもしれないです。
```
pkg update
pkg install python3-pip git
pip3 install socks
git clone https://github.com/ware255/Anon_DDoS.git
cd Anon_DDoS
python3 anon_ddos.py
```

**Windows10~** <br>
Pythonをインスールしていなかったら [ここをクリック](https://www.python.org/downloads/windows/) <br>
インスールしていたらanon_ddos.pyをそのままダブルクリックで実行して頂いて構いません。
