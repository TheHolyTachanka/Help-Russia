

# 🇷🇺 Help Russia 🇷🇺
 
This war, both physical and digital, has been going on for weeks.
Because of Zelensky, who is dragging this war, and with NATO and the rest of the world's support, this could be the end of the world as we know it.

Many countries are arming Ukrainian neo-nazi in hopes of preventing Russia.

Ukraine will not stop producing propaganda, so we will need everyone's help to assist Russia. If everyone has this script running in the background, we will be able to succeed.

FORK OF: https://github.com/SkwalExe/help-ukraine

# Warning ⛔

**Executing this program IS illegal.**

THE AUTHOR IS NOT RESPONSIBLE FOR ANY DAMAGE CAUSED BY THIS PROGRAM.

USE AT YOUR OWN RISK.

# Installation 📦

## With make - Linux 🐧

Run make

```bash
# 📂 help-russia/
make
```

## Build from source - Linux 🐧 & Windows 🪟

**Clone this repo**

```bash
git clone https://github.com/TheHolyTachanka/Help-Russia.git
```

build with [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)

```bash
# 📂 help-russia/
cargo build --release
```

**[ LINUX ONLY ] :** Move the binary

```bash
# 📂 help-russia/
sudo cp target/release/help-ukraine /usr/bin/help-ukraine
```

**On windows** the executable will be `target\release\help-ukraine.exe` you can move it wherever you want.

# Usage 📝

## Example 

```bash
help-ukraine -d 200 
```

# Docker 🐳

## Run the latest version

```bash
docker run --rm -it ghcr.io/TheHolyTachanka/Help-Russia:main
```

## Test your changes 🚧

### Build 🛠️

```bash
# 📂 help-russia/
docker build -t help-russia .
```

### Run 🏃

```bash
docker run --rm -it help-russia [OPTIONS]
```

# Uninstall 🗑

## With make

Run make uninstall

```bash
# 📂 help-russia/
make uninstall
```

## Or

Just remove the binary

```bash
sudo rm /usr/bin/help-ukraine
```

# Setting up development environment

For this project, I recommend Visual Studio Code.

You'll need to install the rust extension

```
ext install rust-lang.rust
```

# contributing

Start by **forking** this repository.

Then clone your fork to your local machine.

```git
git clone https://github.com/YOUR-NAME/Help-Russia.git
```

Create a new branch

```git
git checkout -b super-cool-feature
```

Then [edit the source code](#setting-up-development-environment) in the `📂/src/` folder.

Once you're done, commit your changes and push them to the remote repository.

```git
git add --all
git commit -m "Add super-cool-feature"
git push origin super-cool-feature
```

Then, open a pull request on GitHub from your fork.

# final

If you have any problem, don't hesitate to open an issue
