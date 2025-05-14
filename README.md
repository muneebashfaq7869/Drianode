# Drianode Guide
# 1st Command
sudo apt update && sudo apt upgrade -y
# 2nd Command (create screen)
screen -S dria
# 3rd command ( install launcher)
curl -fsSL https://dria.co/launcher | bash
# 4th command ( start node )
sudo dkn-compute-launcher start
# 5th commmand ( USE THESE 2 commands if get ERROR )
ls ~/.dria/bin
export PATH="$HOME/.dria/bin:$PATH"
# NOW PASTE 4TH COMMAND AND START NODE 
# IF STILL GET SAME ERROR THEN REPEAT 3RD AND 5TH TWO COMMAND THEN AGAIN START IT USING 4TH COMMAND 
