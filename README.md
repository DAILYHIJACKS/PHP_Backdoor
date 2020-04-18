Metasploit Payload 'php/meterpreter/reverse_https' 

On Line 10 and 11 you can directly add
    $ip   = 'your IP'
    $port = 'your PORT'

'file_get_contents' was used because in case your IP gets change you can just visit
the Text file and change the host name in host.txt. 

And always have your Text file (Both: host.txt and port.txt) hosted some where safe on your 
hosting as when you loose backdoor you wont get the shell again so if you have access to these 2 files
you can just change the IP and Port with the new one.

Thanks and sorry for poor README. lol



Author #Qirit0
