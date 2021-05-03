# HW18-POA

Node1: 0x5bcab7F4255496e0c5110990B492Da585994d1FD    password: node1
Node2: 0x701CAA88a468a2f19Bb87B9067A4f45B0d38c386    password: node2

./geth --datadir node1 --unlock "0x5bcab7F4255496e0c5110990B492Da585994d1FD" --mine --rpc --allow-insecure-unlock

./geth --datadir node2 --unlock "0x701CAA88a468a2f19Bb87B9067A4f45B0d38c386" --mine --port 30304 --bootnodes "enode://3cb8c21aceff940f6cb548610ba52c5e0ad1775f5dbf3d9740ef2f9ce5b7c9cb4b3b331a6ac6f4574609e58ffc84b3db841efffd6994e4510f68cc3cba3516a3@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock

