# T3rn
Auto Upgrade T3rn Node

Instruction 

1. Go to https://blastapi.io and create your API KEY for RPC 
2. Download upgrade.sh 
   - `wget https://raw.githubusercontent.com/Moniak13/T3rn/refs/heads/main/upgrade`
2. or just do 
   - nano upgrade.sh
     copy raw code and pass it to file 
     CTRL+X+Y
3. Run Screen 
   - `screen -S <name>`    <---- New screen for Node
   - `screen -R <name>`    <---- if u have screen created
4. chmod +x upgrade
5. Run upgrade
   - `./upgrade`
6. If its all done 
   - CTRL + A + D
