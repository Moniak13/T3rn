# T3rn
<h1>Set up T3rn Node</h1>

<h2>Default folder - t3rn</h2>

Install library
   - `apt install screen`

<h1>Instruction To Run Node</h1>

1. Create Folder
   - `mkdir t3rn`
   - `cd t3rn` 
3. Run Screen
   - `screen -S t3rn`
4. Download upgrade 
   - `wget https://raw.githubusercontent.com/Moniak13/T3rn/refs/heads/main/Node`
5. Give permission
   - `chmod +x Node`
6. Run upgrade
   - `./Node`
7. Copy your private key
8. Go to https://blastapi.io and create your API KEY for RPC 
   - Copy only Project ID
9. Set gas gwei 
10. Close sesion
    - `CTRL + A + D`

<h1>Upgrade Node without reconfigurate</h1>

<h2>Default folder - t3rn</h2>

1. Open screen sesion
      - `screen -r t3rn`
2. Stop Node
   - `CTRL + C`
3. Switch folder
   - `cd`
   - `cd t3rn`
4. Download files
   - `wget https://raw.githubusercontent.com/Moniak13/T3rn/refs/heads/main/Upgrade`
5. Give permission
   - `chmod +x Upgrade`
6. Run
   - `./Upgrade`
7. Switch folder
   - `cd executor/executor/bin`
8. Give permission
   - `chmod +x t3rnAutorestart.sh`
9. Run Autorestart
   - `./t3rnAutorestart.sh`
10. Close sesion
    - `CTRL + A + D`
  
<h3> If u wanna get back to sesion </h3>
<h3>screen -r t3rn</h3>
