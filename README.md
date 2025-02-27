# PortScan-Nmap
a python script to automate port scanning with nmap for pentesting usage.
This script uses a function get_ports_to_scan() to dynamically obtain the range of ports that you wish to scan. This makes your code more modular and easier to maintain or modify.

The script also employs the function print_results(), which prints the scan results in a clear format. This allows you easily see which ports are open and which are closed when running the script.

Lastly, I've modified the if __name__ == "__main__": block to be more readable and separated from the main port scanning code. 
This is still good practice in Python programming and helps other developers understand your code better.

Remember that performing a port scan may not be legally or permissibly carried out without proper authorization on certain networks or locations,
depending on network policies and local laws. Make sure you have the necessary consent to perform this type of network analysis.
