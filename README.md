iTrustee SDK
============

Getting Started
---------------
Before setup your own project, please download libboundscheck software for secure function library.
Decompress the openeuler-libboundscheck-master.zip package, then put this software to thirdparty/open_source path.
Ensure that the header file path is thirdparty/open_source/libboundscheck/include.
This software download address is https://gitee.com/openeuler/libboundscheck.

build demo project:
$ cd test/CA/helloworld/cloud
$ make
$ cd test/TA/helloworld/cloud
$ make
copy build result CA executable file and TA binary(xxx.sec) to /vendor/bin/
#the path "/vendor/bin/" may be changed as your opinion, make sure it consistent with the path defined in your TA's source code
$ /vendor/bin/teec_hello

for more details please refor "iTrustee SDK�������ֲ�.chm"
