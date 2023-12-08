██████╗  █████╗ ██╗   ██╗██████╗  ██████╗ ███╗   ███╗██████╗  ██████╗  ██████╗ 
██╔══██╗██╔══██╗╚██╗ ██╔╝██╔══██╗██╔═══██╗████╗ ████║╚════██╗██╔═████╗██╔═████╗
██████╔╝███████║ ╚████╔╝ ██║  ██║██║   ██║██╔████╔██║ █████╔╝██║██╔██║██║██╔██║
██╔═══╝ ██╔══██║  ╚██╔╝  ██║  ██║██║   ██║██║╚██╔╝██║██╔═══╝ ████╔╝██║████╔╝██║
██║     ██║  ██║   ██║   ██████╔╝╚██████╔╝██║ ╚═╝ ██║███████╗╚██████╔╝╚██████╔╝
╚═╝     ╚═╝  ╚═╝   ╚═╝   ╚═════╝  ╚═════╝ ╚═╝     ╚═╝╚══════╝ ╚═════╝  ╚═════╝
README

paydom200 consists of three scripts:

+ 200check.py - checks ip addresses from file ip_addresses.txt and saves ip with answer "200" to file input.txt

+ domCheck.py - checks ip addresses from file input.txt for domain name. Has two outputs: output.xls(table with ip addresses and domains), dom.txt (list of unique domains).

+ payCheck.py - checks domains from dom.txt file for connected payment systems. Domains with found payment systems are saved to file payDom.txt


paydom200.py runs these scripts sequentially, also you can run them in any order by yourself if you have the necessary data.
