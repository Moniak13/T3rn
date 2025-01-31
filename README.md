# T3rn
Set up T3rn Node

Install library
   - `apt install screen`

Instruction To Run Node 

1. Create Folder
   - `mkdir t3rn`
   - `cd t3rn` 
3. Run Screen
   - `screen -S t3rn`
4. Go to https://blastapi.io and create your API KEY for RPC 
   - Copy only Project ID
5. Download upgrade 
   - `wget https://raw.githubusercontent.com/Moniak13/T3rn/refs/heads/main/Node`
6. chmod +x upgrade
7. Run upgrade
   - `./upgrade`
8. Close sesion 
   - `CTRL + A + D`

Upgrade Node without reconfigurate config
1. Open screen sesion
      - `screen -r t3rn`
2. Stop Node
   - `CTRL + C`
3. Download files
   - `wget https://raw.githubusercontent.com/Moniak13/T3rn/refs/heads/main/Upgrade`
4. Give permission
   - `chmod + x Upgrade`
5. Run
   - `./Upgrade`
6. Close sesion 
   - `CTRL + A + D`

