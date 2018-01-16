# PathDiv
PathDiv tool performs a multi-homed multipath trace in fullmesh manner and calculate the Path Diversiy in the context of rMPTCP path management. The tool is based on the "traceroute(8) for Linux" version 2.1.0 by Dmitry Butskoy. 

Installation instructions:

1: Download Version 2.1.0 and change the name of the folder /traceroute to /PathDiv.

2: Replace the traceroute.c in the folder /PathDiv with the one available here.

3: In terminal, change directory (CD) to the downloaded folder (with makefiles)

4: run terminal commands "make" and "sudo make install". Ignore warnings.


Tool Operation: 

1: Start the PathDiv tool by typing the terminal command "PathDiv No_of_src_interfaces No_of_dest_interfaces" for example "PathDiv 3 3" or "PathDiv 2 2".

2: Enter the IP address or DNS for each source and each destination interface when prompted for it.

3: The sequence of entry of the Network addresses is important and decides the indices of the subflows and related properties.

4: Results of the MultihomedTrace are displayed followed by the PathDiversity metrics in the context of rMPTCP path management.
