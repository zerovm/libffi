## Building for ZeroVM

Prerequisite: install toolchain from [zerovm/toolchain](https://github.com/zerovm/toolchain)

Then run:

	./configure --host=x86_64-nacl --prefix=$ZVM_PREFIX/x86_64-nacl
	make
	make install

