# Crack-A-Lot

 in the hint"confidential file "  there was thousands of passwords,so i asked chat gpt to give a method so it recommended brute force attack 
so i searched for bssid in "TOP_SECRET.pcap" file 
command :
ctrl+f
searched for packet bssid
got bssid :f6:0f:6c:4d:06:7c
then used aircrack-ng for brute force attack
command which i used 
  aircrack-ng -w the_secret_flag.txt -b f6:0f:6c:4d:06:7c TOP_SECRET.pcap
then i got the flag
