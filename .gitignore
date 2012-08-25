#!/bin/bash
#My Program
echo ""
echo ""
echo "########################################################################################################"
echo "                             AUTHOR: HARSHAL VAIDYA -- Hard Coder"
echo "        Kindly enter the details appropriately,program is fully implemented in BASH SCRIPT"
echo "         Syntax oriented scripting..BEWARE.. Otherwise, chances of failure of verification "
echo "########################################################################################################"
sleep 5
j=public_html
echo ""
echo ""
echo "=============================="
echo "ENTER DOMAIN NAME"
echo "=============================="
read domain
echo ""
echo "=============================="
echo "ENTER USERNAME"
echo "=============================="
read i
echo ""
cd /home
sleep 1
result=$(echo "$( readlink -f "$( dirname "$home" )" )/$( basename "$i" )/$(basename "$j")")
cd $result
if [ ! -d "$result" ];   then
echo "SOMETHING ENTERED WRONGLY, PATH COULDN'T BE FOND, hENCE, CAN'T PROCEED"
exit
fi
echo "=============================="
echo "YOUR WORKING DIRECTORY IS : "
echo "=============================="
sleep 2
pwd
echo ""
echo "WORKING DIRECTORY EXISTS"
sleep 1
echo "Hence Proceeding ........"
sleep 1
echo ""
echo "=============================="
echo "ENTER VERIFICATION CODE (usually like google12345asd35.html)"
echo "=============================="
read code
touch $code
echo "=============================="
echo "ENTER FULL VERIFICATION CODE : (usually like  google-site-verification: google12345asd35.html ) "
echo "=============================="
read text
for f in $code ; do
    echo "$text" >> $code
done
echo "..."
sleep 1
echo ".."
sleep 1
echo "."
sleep 1
echo "CODE ADDED SUCCESSFULLY "
echo ""
sleep 2
echo "=============================="
echo "INSTALLING GOOGLE APPS"
echo "=============================="
sleep 1
echo "..."
sleep 1
echo ".."
sleep 1
echo "."
sleep 1
echo "."
install-mx $domain gapps
sleep 2
echo "============================="
echo "FIXING PERMISSIONS"
echo "============================="
sleep 3
perms
echo "============================="
echo ""
echo "Yawh !!! Its done ;) "
echo ""
echo "########################################################################################################"
echo ""
echo "                            @@@##    REGARDS : HARSHAL VAIDYA    ##@@@"
echo ""
echo "                                  EAT  #  CODE  # DRINK  # SLEEP"
echo ""
echo "########################################################################################################"
