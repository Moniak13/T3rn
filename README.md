# T3rn
Auto Upgrade T3rn Node

Instruction 

1. Go to https://blastapi.io and create your API KEY for RPC 
   - Copy only Project ID
2. Download upgrade 
   - `wget https://raw.githubusercontent.com/Moniak13/T3rn/refs/heads/main/upgrade`
3. Run Screen
   - install screen `apt install screen`
   - `screen -S <name>`    <---- New screen for Node
   - `screen -R <name>`    <---- if u have screen created
5. chmod +x upgrade
6. Run upgrade
   - `./upgrade`
7. If its all done 
   - CTRL + A + D
