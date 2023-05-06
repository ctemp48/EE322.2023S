Results of hash_value.py:
```
The hash for 1 is: 1
The hash for 1.0 is: 1
The hash for 3.14 is: 322818021289917443
The hash for Python is: -5287743072203781517
The hash for a tuple of vowels is: 5854703825554577181
The hash for an object of person is: -812466642214332374
(base) christiantemplin@Christians-Air lesson10 % python3 hash_value.py
The hash for 1 is: 1
The hash for 1.0 is: 1
The hash for 3.14 is: 322818021289917443
The hash for Python is: 4630659274660012071
The hash for a tuple of vowels is: -2537103975357155131
The hash for an object of person is: 4574822800271795628
(base) christiantemplin@Christians-Air lesson10 % 
```
It can be seen that integer and float values have the same hash, but strings and objects do not.


mining coins with snakecoin.py :
```
Block #1 has been added to the blockchain!
Hash: fa40eb6c3985d7aa0e617e1d9a13955fa2532e6d0cc7c8831af70962ec0ac4ee

Block #2 has been added to the blockchain!
Hash: 40497fb8cca0fe6095648b323b08761298df50df5b4e085d05da4f192ebc4aa0

Block #3 has been added to the blockchain!
Hash: aa55eac8dc4f9bb7de895fd0c4849146668a730280969a28f565bb30dbe50dd9

Block #4 has been added to the blockchain!
Hash: 3ec36a4c59f0500fdc5bbba2ac558d4cf69e1887550fb37a45e8f52d997fd2f5

Block #5 has been added to the blockchain!
Hash: 084176ebf0a1ae5d6e16f2c3a4e4a74928f311e58c0f16fac8a1a8a6077fbe1b

Block #6 has been added to the blockchain!
Hash: bf59cb107f07452488916c7b8220ebb12b85fecef285dc93766840d0237ac2c6

Block #7 has been added to the blockchain!
Hash: d627d48bcace57d84abb06f4003fe12153981900d52811d25b38a9dc51ae2823

Block #8 has been added to the blockchain!
Hash: b86ce0c473c15b9277e1478709dbd4dc3a4b47c24ad2829dad0f19311d19ac64

Block #9 has been added to the blockchain!
Hash: ae708889b1ac32169ca38a930d70b5b075ac448c761a1d41ce557ba6ecf2a33e

Block #10 has been added to the blockchain!
Hash: bec1583d9af715b15cebe63b1af3cbdb56ce9c7b3dff482f9bf826f50059ced0

Block #11 has been added to the blockchain!
Hash: 0be72bc6fb927fba60ae1b533187e3672265ccd47fae8339212275b062e7c4e2

Block #12 has been added to the blockchain!
Hash: 8f29f4c032ed663ea97d0f6a9c4782a6c7902edee186562030c70011caca8206

Block #13 has been added to the blockchain!
Hash: 05208b8209c9b5d32cd3e0bb4b47a08527f41ae507a293ee326c1ab47f4875cd

Block #14 has been added to the blockchain!
Hash: 69e960a99b056810406fe1ec2d23966a6de52b8f8ca9d1127b21aee1af3ab23a

Block #15 has been added to the blockchain!
Hash: 8f6471773348fe30255c55309e3ae3f9ee6e1a2941530887b299bca467e8f68b

Block #16 has been added to the blockchain!
Hash: f1777a8305e250634fd327b9281bf9a697e92565c1e30e65316a5959b8c6b7de

Block #17 has been added to the blockchain!
Hash: d65b1374bfbe823eb50a04d79ae660ff6e19ba9453b7f2dcc81b8b915ed5b55c

Block #18 has been added to the blockchain!
Hash: db5a9df5535c0c1e33c5340b3d81b9c3c1b8ea8a8391ea2d6aff17e9489c7a34

Block #19 has been added to the blockchain!
Hash: 83bf2cac3dfe687ede705f70089a333da1344b332e3dd9851fa3eeec983586c5

Block #20 has been added to the blockchain!
Hash: 8a82fcec04cfdc14aa779dc32650e8f9b3785a50e5d62bdd24ab7f42c63a8c11

```
Terminal 1 blockchain server:
```
127.0.0.1 - - [05/May/2023 21:22:30] "GET /chain HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:22:59] "POST /new_transaction HTTP/1.1" 201 -
127.0.0.1 - - [05/May/2023 21:22:59] "GET /chain HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:23:11] "GET /chain HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:23:51] "GET /chain HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:24:08] "POST /new_transaction HTTP/1.1" 201 -
127.0.0.1 - - [05/May/2023 21:24:08] "GET /chain HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:24:11] "GET /chain HTTP/1.1" 200 -
```

Terminal 2 blockchain server:
```
127.0.0.1 - - [05/May/2023 21:22:30] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:22:31] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [05/May/2023 21:22:59] "POST /submit HTTP/1.1" 302 -
127.0.0.1 - - [05/May/2023 21:22:59] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:23:11] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:23:51] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:23:57] "GET /index HTTP/1.1" 404 -
127.0.0.1 - - [05/May/2023 21:24:08] "POST /submit HTTP/1.1" 302 -
127.0.0.1 - - [05/May/2023 21:24:08] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 21:24:11] "GET / HTTP/1.1" 200 -
```

