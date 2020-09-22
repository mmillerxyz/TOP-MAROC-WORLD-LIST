
# TOP-MAROC-WORLD-LIST
WPA/WPA2 MAROC WORLD LIST
# FAST-WPA
HAVE EASY PASSWD LIKE 12345678 NAME+YEAR OR NAME@YEAR ...




<img src="https://i.imgur.com/6kSTLSH.png">
<P> this world list is just for study and improve security of WPA 
##################################################################################

# 8 num
# 9 num
# wpskey
# 3-4 num
# TOP-MAROC-WORLD-LIST
# Collection-WPA
<P> ######################################################
<P> https://mega.nz/folder/p4lCTIaK#Szemg7V395XjonBDHmWmUA
<P> ######################################################

# ALL THIS FILES CREATE  OR MODIFIER WITH

<P> notepad++
<P> maskprocessor
<P> hjsplit
<P> combinator
  
<P> #########################################################################
<P> 	cat wpa.txt | awk 'length >=8 && length <=63' | uniq > new-wordlist.txt 
<P> 	grep -E '^.{8,63}$' wpa.txt | sort -t: -u -k1,1 > new-wordlist.txt 
<P>  cat wpa.txt | sort | uniq | pw-inspector -m 8 -M 63 > new-wordlist.txt
<P> #########################################################################
 
