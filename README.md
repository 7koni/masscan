
# MASSCAN4WINDOWS

Fork of [Masscan](https://github.com/robertdavidgraham/masscan) with minimal changes to build it on Windows.  
Don't expect any competitive results.  

# Download

Check out the [latest release](https://github.com/7koni/masscan4windows/releases/latest).

# Build

Install [MSYS2](https://www.msys2.org/), carefully following the instructions on that page.  

Instead of `mingw-w64-x86_64-toolchain`, install `mingw-w64-i686-toolchain`  

(Yep, that would be x32, no luck with 64 so far)  

Clone this repo, launch `MSYS2 MinGW 32-bit` terminal, cd to repo folder, run `make`.  

`masscan.exe` will be waiting for you in the `bin` folder.  

# Usage

For details on usage and authorship, please refer to the [original README.MD](https://github.com/robertdavidgraham/masscan/blob/master/README.md)

# Authors

This tool created by Robert Graham:  
email: robert_david_graham@yahoo.com  
twitter: @ErrataRob  
