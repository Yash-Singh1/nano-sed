# `nano-sed`

Syntax highlighting for sed in the `nano` code editor.

## Installation

Run:

```sh
git clone https://github.com/Yash-Singh1/nano-sed.git
cd nano-sed/
```

Then run:

### Ubuntu/Debian

```sh
sudo cp sed.nanorc /usr/share/nano/
```

### Mac

```sh
sudo -i
mkdir /usr/local/share/nano/
echo 'include "/usr/share/nano/*.nanorc"' >> /etc/nanorc
cp sed.nanorc /usr/local/share/nano/
```

### Windows

<!-- markdownlint-disable-next-line MD036 -->
**Note: Remember to run as administrator**

```sh
cp sed.nanorc /usr/share/nano/
```

## Usage

`*.sed` files should be syntax highlighted.
