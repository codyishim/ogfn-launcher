# ogfn-launcher
ogfn launcher  for everyone 


required
https://rust-lang.org/tools/install/    /
https://nodejs.org/dist/v24.12.0/node-v24.12.0-x64.msi


https://drive.google.com/drive/folders/15wcoG0vuE_dVEA8UCW-z8IU9Rd515gd3?usp=sharing

how to use open vs code go to file and open the launcher folder then u need to open terminal and open new one and here are the commands/ 


Install rust (rust-lang.org)
Install bun (bun.sh)
Install Node.js (nodejs.org)

after installing, configure ur launcher in env
change the logo in public/ and src-tauri -> icons

go to src-tauri -> tauri.conf.json

change the name and version to your choice, etc.
finally,

Open terminal

Run the following commands
bun install
bun tauri dev (to test)
bun tauri build (to release)

After you run bun tauri build you should see your msi installer in src-tauri/target/release/bundle/msi 


