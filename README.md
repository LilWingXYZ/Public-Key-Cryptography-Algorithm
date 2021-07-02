# Research-and-Use-of-Public-Key-Cryptography-Algorithm

源代码程序是ipynb文件，在Jupyter Notebook或者Colab等上均可打开，或者也可以将代码直接复制改为py文件。

在源程序文件夹下添加一个 plaintext.txt 文件就可直接运行该ipynb文件，plaintext.txt里是明文内容，可自行编写，如“21200211047xyz”。

首次运行将main里的
	generate_key('key1')
	generate_key('key2')
两行代码取消注释。
运行完毕后会产生'publickey1.txt', 'privatekey1.txt','publickey2.txt', 'privatekey2.txt'四个文件。

首次运行完之后每次运行都将main里的
	generate_key('key1')
	generate_key('key2')
两行代码注释掉。否则'publickey1.txt', 'privatekey1.txt','publickey2.txt', 'privatekey2.txt'里的密钥内容会被更改。

之后按照要求使用不同的公钥和私钥进行加解密即可，代码里有注释。
