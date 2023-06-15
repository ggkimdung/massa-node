# massa-node
Run node massa testnet
---------------------Run bin------------------------------
wget https://github.com/massalabs/massa/releases
tar -xvf

- RUN NODE
	cd massa/massa-node/ && ./massa-node -p Cugkodc1 |& tee logs.txt
	
	//while true; do ./massa-node -p Cugkodc1 |& tee logs.txt; done
- RUN CLIENT
	cd massa/massa-client/ && ./massa-client -w

- Buy rolls: Should be like this ‘ buy_rolls <address> <roll count> <fee> ‘ //1 space 0
mjh:	buy_rolls AU12EphWyvfrxjfPypcwVWB6cFrnNFjjW1GS7Mt7Zi3EYtuCvFTDd 1 0
bog:	buy_rolls AU1hMGrpkQmXvhbAepbM5uqLaRcJwpwXeZvtsrzkLWZViuoqNsTT 1 0

- Sẽ mất chưa đầy một phút để danh sách của bạn trở thành bản cuối cùng, hãy kiểm tra bằng:
	wallet_info
- Yêu cầu nút của bạn bắt đầu đặt cược với các cuộn của bạn
- Nhận địa chỉ có cuộn trong ví của bạn:
	wallet_info
- Đăng ký địa chỉ của bạn để nút của bạn bắt đầu đặt cọc với nó:
mjh:	node_start_staking AU12EphWyvfrxjfPypcwVWB6cFrnNFjjW1GS7Mt7Zi3EYtuCvFTDd	
bog:	node_start_staking AU1hMGrpkQmXvhbAepbM5uqLaRcJwpwXeZvtsrzkLWZViuoqNsTT
- Discord
mjh	node_testnet_rewards_program_ownership_proof AU12EphWyvfrxjfPypcwVWB6cFrnNFjjW1GS7Mt7Zi3EYtuCvFTDd 638163877615501364
bog	node_testnet_rewards_program_ownership_proof AU1hMGrpkQmXvhbAepbM5uqLaRcJwpwXeZvtsrzkLWZViuoqNsTT 910892007805837333
