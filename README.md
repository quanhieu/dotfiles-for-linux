# dotfiles

> 💻 dotfiles and 🚀 more.

### 🧰 general installation

```sh
yes | /bin/bash -c "$(curl -sSL https://raw.githubusercontent.com/quanhieu/dotfiles-for-linux/main/install.sh)"
```

### ⚙️ ibus-unikey

```sh
ibus-daemon -drx
sudo apt install -y ibus-unikey
ibus restart
ibus-setup
gsettings set org.gnome.desktop.input-sources sources "[('xkb', 'us'), ('ibus', 'Unikey')]"
```

Add **ibus-daemon -drx** to **startup**

### 🔑 generating a new SSH key

```sh
ssh-keygen -t rsa -b 4096 -C "hieutq1188@gmail.com"
cat ~/.ssh/id_rsa.pub
```

### 💅 other
- [ibus-bamboo](https://github.com/BambooEngine/ibus-bamboo)
- [night-owl-pantheon](https://github.com/harrytran103/night-owl-pantheon) - 🌌🦉Night Owl theme for Pantheon terminal.
- [dracula-pantheon](https://github.com/harrytran103/dracula-pantheon) - 🧛🏻‍♂️ Dark theme for Pantheon terminal.
- [mediumship](https://github.com/swapagarwal/mediumship) - 📚 Read all Medium stories for free!
- [golangci-lint](https://golangci-lint.run/usage/integrations/)
- [protoc](http://google.github.io/proto-lens/installing-protoc.html)
- [Telegram](https://desktop.telegram.org/)
- [Dockstation](https://dockstation.io/)
- [BloomRPC](https://github.com/uw-labs/bloomrpc)

## 🔖 license

MIT
