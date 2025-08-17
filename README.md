# odin-recipes
In this project i will just create a simple website for recipes by following the instruction from the odini project..
I will be implementing the things i have learnt till now from the odin project..

1. At first i have create a repo inside my github account named it as odin_recipes
2. I have create a ssh key for my github account..
    ->first open the gitbash terminal
    ->then type ssh-keygen -t ed25519 -C"nagarjunak472@gmail.com
    -> here the ssh-keygen is the main command which tells to generate the ssh key and the -t ed25519 is the flag which tell to create the key under thisencryption algorithm.
    ->then press enter to store the key in the default location then press enter twice to skip presspase then ..
    ->cat ~/.ssh/id_ed25519.pub type this to show the key
    ->cat is used to display the content ~ is used a A shortcut for your user's home directory. /.ssh/: The hidden folder inside your home directory where SSH keys and other configuration files are stored by default.id_ed25519.pub: The actual public key file. The .pub extension signifies that it's the public part of the key pair, which is safe to share.
3. Then i have added the key in the github by going to profile and settings then there selcet the ssh and gpg key section in that add new there you add the name and then add the ssh key which you copied froom the terminal..then create thats it..
4. copie the code and then open the vscode terminal then do connect with github account by giving user name and mail and then clone the repo..