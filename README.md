Hello! 🐧 I made this because I got tired of trying to remember weird Linux commands. I turned them into simple words so it's easier for everyone to use.
A few examples:

    Instead of ls -lah, just type list.
    Instead of cd, just type change.
    Instead of sudo, just type keep.
    Instead of echo, just type say.

You can type mycommands whenever you want to see the rest of the list!
How to install it:
Step 1: Create the file by typing nano ~/my_universal_aliases.sh. Copy the code from this repo, paste it in, save, and exit.
Step 2: Tell your terminal to load it. If you use Fish, run:
echo "source ~/my_universal_aliases.sh" >> ~/.config/fish/config.fish
If you use Bash or Zsh, run:
echo "source ~/my_universal_aliases.sh" >> ~/.bashrc
Step 3: Make it work for Root (the admin user) by running these two:
sudo cp ~/my_universal_aliases.sh /root/my_universal_aliases.sh
sudo sh -c 'echo "source /root/my_universal_aliases.sh" >> /root/.bashrc'
Step 4: Restart your terminal and type say hello to see if it worked!
