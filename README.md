# Pcap Parser

Python utility to parse pcap files and extract flow-related information from
them.

## Getting started:

This utility requires macOS. You need to have Python 3 installed.

Also make sure to have [Wireshark](https://www.wireshark.org/download.html)
installed on your macOS.

Set up the environment:

```bash
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

Run the parser:

```bash
$ python parser.py <output_csv_file> <pcap_file> [<pcap_file> ...]
```
