# OSCP-Automation
A collection of personal scripts used in hacking excercises.
Consider a majority of them in beta- useable but I will probably improve them as time goes on. :)
https://c-cracks.tumblr.com/

## enum.sh
* Performs an Nmap scan on the provided IP and further Wfuzz and Nikto scans on discovered web servers (per port found to be a web server)
* Very basic in nature and I'm sure there's more intuitive tools out there; I'm building my own collection of scan automation tools.

## privesc.sh
* Automation of info gathering for Linux privilege escalation
* Can be used even if upload to the victim isn't possible as a reference

## test-methods.sh
* Sends requests under different methods to the provided URL
* Appearance of the output leaves alot to be desired; as long as it's clear where each request ends I don't mind. xD

## brute-force.sh
* Brute force web applications with cURL
* Handles GET and POST requests currently with the options to add cookies and/or headers to the request
* POST has been tested thoroughly against the VM Mr Robot with the right credentials being discovered and I have also tested the addition of headers and/or cookies.

## To come(?):
* privesc for Windows (eugh...)
  * This will likely come in a few weeks.
