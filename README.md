# my-sway-noctalia-shell-dots

# ok first you have to clone the repo in where ever you want (i.e Downloads) by running (ensure you have git installed)

git clone https://github.com/Christine-oss-web/my-sway-noctalia-shell-dots.git 

# after that copy the dots over to ~/.config by running 

cp -r ~/Downloads/alacritty ~/Downloads/btop ~/Downloads/cava ~/Downloads/sway ~/.config 

# then edit the configs to your liking and needs

# after that rename noctalia-config.toml to config.toml 

mv ~/Downloads/noctalia-config.toml ~/Downloads/config.toml

# then copy it 

cp ~/Downloads/config.toml ~/.config

# then delete all the folders and files from the repo that is on your Downloads folder 

rm -rf ~/Downloads/my-sway-noctalia-shell-dots 

# thats it 
