# Research network protocol analyzers

In this activity, I focused on the two network protocol analyzers: Wireshark and tcpdump. My goal was to gain a basic understanding of the Wireshark and tcpdump, how they work, and what their features are.

Disclaimer:

A network protocol analyzer (packet sniffer) is a tool designed to capture and analyze data traffic within a network. Network protocol analyzers help security analysts examine and understand the network traffic flows.

<img src="https://github.com/melaniedaniel7/Research-network-protocol-analyzers/blob/92e9e99945c01951febb2fedd8d2e10b2e4a40c4/network%20protocol%20analyzers.png" width="800" />

### Wireshark
- What software or equipment is required to access and use the tool? Is the tool open-source or proprietary?
  
  Wireshark runs on most operating systems (Windows, macOS, Linux). It requires an internet-capable device and sometimes elevated privileges to capture network traffic.
  
- What type of user interface or layout does the tool use?
  
  Wireshark is open-source.
  
- How do security analysts typically use the tool? What are the recommended usage scenarios for each tool?

  Analysts use Wireshark for in-depth packet analysis, troubleshooting network issues, and identifying malicious traffic. It’s ideal for capturing and analyzing data in real-time.
  
- How does the tool handle capturing, analyzing, and filtering network traffic?

  Wireshark captures packets and categorizes them by protocol. Analysts can apply filters (e.g., IP addresses, ports) to focus on specific data and gain insights.
  
- Are there any limitations or considerations for using this tool?

  Wireshark can be complex for beginners and may require a lot of memory for large captures. It is not typically used on high-traffic networks because of the high resource demand.

### tcpdump
- What software or equipment is required to access and use the tool? Is the tool open-source or proprietary?

  tcpdump is typically used on UNIX-based systems, though it can be installed on Windows with additional configuration. It requires a command-line interface (CLI) and usually elevated privileges.
  
- What type of user interface or layout does the tool use?

  tcpdump is open-source.

- How do security analysts typically use the tool? What are the recommended usage scenarios for each tool?

  tcpdump operates via CLI, outputting text-based data in real-time with minimal formatting.

- How does the tool handle capturing, analyzing, and filtering network traffic?

  Analysts use tcpdump for quick packet captures, particularly on servers or systems without a GUI. It’s useful for filtering specific packets or network traffic quickly.

- Are there any limitations or considerations for using this tool?

  tcpdump lacks a GUI, making it harder to analyze data visually, and has limited protocol decoders compared to Wireshark. For complex analyses, saved files are often imported into Wireshark.
