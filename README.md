# ucl-vpn
A simple script allowing you to connect to UCL's VPN using openconnect instead of Cisco's annoying, buggy AnyConnect.

## Dependencies
* MacOS: `brew install openconnect curl`
* Ubuntu: `apt-get install openconnect curl`

## Usage
Make sure both files are executable: `chmod +x <files>`.
Optionally, create a symlink to `ucl` in a folder that is on your PATH.

Then connect to UCL's VPN simply by running `ucl`.

## Credit
script adapted from https://blogs.ucl.ac.uk/dh/2015/09/18/tutorial-ucl-vpn-linux/
