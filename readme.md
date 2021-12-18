# Ubuntu post install

I constantly make changes to my operating system, I enjoy looking for new options. I have tried arch, manjaro, ubuntu, mint, and a few other things. So I decided to do some "recovery" in a single script (bash). So this is what I have. I'd also like to mention that this script is under development so it may crash and throw errors. I am a web developer so this is kind of a "new world" for me.

### Install

To run this script first of all you need to clone this repository and rename it as ParcaOs.

```bash
# Install git
sudo apt-get install git -y

# Clone this directory. You must be in ~/ path
cd ~/
git clone https://github.com/parcapear/parca_recovery

# Rename the file parca_recovery as ParcaOs
mv ~/parca_recovery ~/ParcaOs

# Move to directory and give permissions to execute
cd ~/ParcaOs
sudo chmod +777 install.sh

# Run the execute
./install.sh
```

Now in your terminal you must see a message about your username of ubuntu like this:

![terminal-image](/Media/terminal-info.png)

After enter your username. If you don't remember, just put the next command in your terminal:

```bash
# Let's check our username
echo $USER
```

And yeah, it will be all. Now just wait for complete the installation. In some cases you will be a prompt open askin about a installation confirmation. **Just put "ok" or "y"**, it depends the situation.