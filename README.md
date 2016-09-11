# c-NodeModule author himanshu sharma

note: nan module is use for complatabilty between version of node .

# first make sure you have 

PYthon , c++11  install 

python (v2.7 recommended, v3.x.x is not supported)
make (or Visual Studio on Windows)
C/C++ compiler toolchain, like GCC (or Visual Studio on Windows)

# then install 

npm install -g node-gyp

for make build of c++ code to run in node

# yes can see the configuration of c++ node module in this binding.gyp

#make build 

node-gyp configure build

which will create a folder build in your working directly

now run node primes.js

you can see the module running
