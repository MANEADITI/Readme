# Splunk

1.	open text editer and write the a simple yara rule:
rule Text
{
   Strings:
             $a: “regopen” nocase wide ascii
   Condition:
             $a
}
2.	Save this file and name it text. yara 
3.	Open command prompt: cd into yara directory
4.	Start yara with our defined rules
5.	Pick a target destination to scan
6.	Start the scan
 

7.	Pick a suspicious file
8.	cd to strings.exe directory. Copy the filepath of the suspicious file
9.	scan with option -a and -u
 

10.	Look for suspicious strings
 




