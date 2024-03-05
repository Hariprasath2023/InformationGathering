# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## pen test tool cateogrie:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## output:
![Screenshot 2024-03-05 195013](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/2740342b-09e6-4a57-8557-c02be4a96864)
Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output
Finding Hosting Company
get further detail by using ip2location.com website.
## output:
![Screenshot 2024-03-05 200958](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/494811ad-d7aa-4914-8c80-1e569cc33deb)

## output:
![Screenshot 2024-03-05 195528](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/8eaac6fd-7fae-4a69-88d3-9c7018540bd4)
#Webserver Fingerprinting:
##netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
###output:
![Screenshot 2024-03-05 205441](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/9b01d621-6d6f-4ed5-b3c2-455273a38c59)

##nmap:
###output:
![Screenshot 2024-03-05 205706](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/c72bc742-b102-435b-bd06-f9a2712b341b)

##whatweb:
###output:
![Screenshot 2024-03-05 205715](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/f720565a-e0af-4e30-97a7-92ea925b80c5)
![image](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/2bc80148-9249-4277-9124-c69bb71748ff)
##httprint
###output
![Screenshot 2024-03-05 210719](https://github.com/Hariprasath2023/InformationGathering/assets/145207783/2735bcda-4edf-45b7-acd6-93840e4a15c6)
##output:
#Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
##output
UDP Traceroute:
sudo traceroute -U www.google.com
##output:


ICMP Traceroute:
sudo traceroute  www.google.com
##output



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
