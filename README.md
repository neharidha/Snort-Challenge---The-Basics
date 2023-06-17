# Snort-Challenge---The-Basics
Task 1:
1.1 Correct Answer: No answer needed

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-

Task2:
2.1 Write rules to detect "all TCP port 80 traffic" packets in the given pcap file.

What is the number of detected packets?

Note: You must answer this question correctly before answering the rest of the questions in this task.

Correct Answer: 328

Investigate the log file.

2.2 What is the destination address of packet 63?

Correct Answer: 145.254.160.237

Investigate the log file.

2.3 What is the ACK number of packet 64?

Correct Answer: 0x38AFFFF3

Investigate the log file.

2.4 What is the SEQ number of packet 62?

Correct Answer: 0x38AFFFF3

Investigate the log file.

2.5 What is the TTL of packet 65?

Correct Answer:128

Investigate the log file.

2.6 What is the source IP of packet 65?

Correct Answer: 145.254.160.237

Investigate the log file.

2.7 What is the source port of packet 65?

Correct Answer: 3372

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-

Task 3
Write rules to detect "all TCP port 21" traffic in the given pcap.

3.1 What is the number of detected packets?

Correct Answer:614

Investigate the log file.

3.2 What is the FTP service name?

Correct Answer: Microsoft FTP Service

Clear the previous log and alarm files.

Deactivate/comment on the old rules.

Write a rule to detect failed FTP login attempts in the given pcap.

3.3 What is the number of detected packets?

Correct Answer:41

Clear the previous log and alarm files.

Deactivate/comment on the old rule.

Write a rule to detect successful FTP logins in the given pcap.

3.4 What is the number of detected packets?

Correct Answer:1

Clear the previous log and alarm files.

Deactivate/comment on the old rule.

Write a rule to detect failed FTP login attempts with a valid username but a bad password or no password.

3.5 What is the number of detected packets?

Correct Answer:42

Clear the previous log and alarm files.

Deactivate/comment on the old rule.

Write a rule to detect failed FTP login attempts with "Administrator" username but a bad password or no password.

3.6 What is the number of detected packets?

Correct Answer:7

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-

Task 4
Write a rule to detect the PNG file in the given pcap.

4.1 Investigate the logs and identify the software name embedded in the packet.

Correct Answer: Adobe ImageReady

Clear the previous log and alarm files.

Deactivate/comment on the old rule.

Write a rule to detect the GIF file in the given pcap.

4.2 Investigate the logs and identify the image format embedded in the packet.

Correct Answer: GIF89a

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-
Task 5:

Write a rule to detect the torrent metafile in the given pcap.

5.1 What is the number of detected packets?

Correct Answer:2

Investigate the log/alarm files.

5.2 What is the name of the torrent application?

Correct Answer:bittorrent

Investigate the log/alarm files.

5.3 What is the MIME (Multipurpose Internet Mail Extensions) type of the torrent metafile?

Correct Answer: application/x-bittorrent

Investigate the log/alarm files.

5.4 What is the hostname of the torrent metafile?

Correct Answer: tracker2.torrentbox.com

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-

Task6:
You can test each ruleset with the following command structure;

sudo snort -c local-X.rules -r mx-1.pcap -A console

Fix the syntax error in local-1.rules file and make it work smoothly.

6.1 What is the number of the detected packets?

Correct Answer:16

Fix the syntax error in local-2.rules file and make it work smoothly.

6.2 What is the number of the detected packets?

Correct Answer:68

Fix the syntax error in local-3.rules file and make it work smoothly.

6.3 What is the number of the detected packets?

Correct Answer:87

Fix the syntax error in local-4.rules file and make it work smoothly.

6.4 What is the number of the detected packets?

Correct Answer:90

Fix the syntax error in local-5.rules file and make it work smoothly.

6.5 What is the number of the detected packets?

Correct Answer:155

Fix the logical error in local-6.rules file and make it work smoothly to create alerts.

6.6 What is the number of the detected packets?

Correct Answer:2

Fix the logical error in local-7.rules file and make it work smoothly to create alerts.

6.7 What is the name of the required option:
Correct Answer: msg

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-

Task 7:
Use the given rule file (local.rules) to investigate the ms1710 exploitation.

7.1 What is the number of detected packets?

Correct Answer: 25154

Clear the previous log and alarm files.

Use local-1.rules empty file to write a new rule to detect payloads containing the "\IPC$" keyword.

7.2 What is the number of detected packets?

Correct Answer:12

Investigate the log/alarm files.

7.3 What is the requested path?

Correct Answer: \\192.168.116.138\IPC$

7.4 What is the CVSS v2 score of the MS17-010 vulnerability?

Correct Answer: 9.3

--­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­--------­-

Task 8:
8.1 Corrct Answer: No answer needed.
