# hello-parodus

Example illustrating simple event interaction with parodus.

[![Apache V2 License](http://img.shields.io/badge/license-Apache%20V2-blue.svg)](https://github.com/Comcast/libparodus/blob/master/LICENSE.txt)

# Building Instructions

```
mkdir build
cd build
cmake ..
make
```
	
# Running the application		
1. Ensure parodus is running first successfully.		
2. Start the application after building, like so - ```./src/hello-parodus -p <parodus local URL> -c <URL to receive parodus response>``` 		
3. From a separate terminal, send curl command to the application through parodus.
