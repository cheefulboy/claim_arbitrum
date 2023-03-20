# claim_arbitrum for mac

1) Install rust: curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
2) Build: cargo build --release
3) Fill the files with private keys and their representative addresses in txt`s
4) Open a .env file and declare an enviromental variable called SOCKET=your_arbitrum_websocket_node ( you can get one from alchemy )
5) Start the script: cargo run
6) Profit


![ExhaustedAdeptAlligator-size_restricted](https://user-images.githubusercontent.com/102196172/226127609-6073aa34-d9fc-43ac-ada2-eb513eb35159.gif)
