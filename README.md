# XssPy - a tool by Fsecurify

XssPy - Finding XSS made easier

Author: Faizan Ahmad (A tool by Fsecurify)

Link: https://www.facebook.com/fsecurify

Usage: XssPy.py website.com (Do not write www.website.com OR http://www.website.com)

Description: XssPy is a python tool for finding Cross Site Scripting vulnerabilities in websites. This tool is the first of its kind. Instead of just checking one page as most of the tools do, this tool traverses the website and find all the links and subdomains first. After that, it starts scanning each and every input on each and every page that it found while its traversal. It uses small yet effective payloads to search for XSS vulnerabilities. 

The tool has been tested parallel with paid Vulnerability Scanners and most of the scanners failed to detect the vulnerabilities that the tool was able to find. Moreover, most paid tools scan only one site whereas XSSPY first finds a lot of subdomains and then scan all the links altogether. The tool comes with:

1) Short Scanning
2) Comprehensive Scanning
3) Finding subdomains
4) Checking every input on every page

With this tool, Cross Site Scripting vulnerabilities have been found in the websites of MIT, Stanford, Duke University, Informatica, Formassembly, ActiveCompaign, Volcanicpixels, Oxford, Motorola, Berkeley and many more.

Installation: Type the following in the terminal.

git clone https://github.com/faizann24/XssPy/ /opt/xsspy


NOTE: Do mail me if you encounter any errors. (fsecurify@gmail.com)

Best Regards
