Use the following scripts to convert from a station.xml file to the
network and station input files for SplitRacer.

available_networks.txt file
1. Run make_network_file.py - need to provide the .xml file on the command line

available_stations.txt file
1. Run make_station_file.py - need to provide the .xml file on the command line

station.lst file
1. Run stations_txt2lst.py

Create a catalogue using the notebook.

Cut waveforms + channel_info.txt files
1. Run cut_waveforms.py
This cuts the waveform files, makes the channel_info.txt file for each
station, and creates a data_request_<station>_<network> file.

Conor Bacon
23 March 2020
