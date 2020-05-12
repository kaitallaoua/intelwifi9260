# intelwifi9260
Bash script that runs commands from a NVIDIA forum post to get the Intel wireless AC-9260 WiFI card working.
Forum post: 

Video format of these instructions on my Youtube channel: https://www.youtube.com/channel/UCabWXnn7SCohfSRl3rWB6dg

Quick instructions:
1. clone this repo:
git clone https://github.com/kaitallaoua/intelwifi9260.git

2. Cd into the directory
cd intelwifi9260

3. Make file executable
chmod +x intelwifi9260

4. Run the file
./intelwifi9260

The commands will run line by line. Eventually you will need to enter your sudo password if its not already persistent in the terminal.
The last command will reboot your Jetson. Upon the reboot your jetson should have working wifi!
