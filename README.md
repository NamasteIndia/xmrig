1. sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
2. git clone https://github.com/namasteindia/aiimagen.git
3. mkdir aiimagegen/build && cd aiimagen/build
4. cmake ..
5. make -j$(nproc)
