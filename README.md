# qlgq
#!/bin/bas
#Program:
# try to calculate 1+2+3+...+ $number user inputs
#History:
#2016/07/06 Qiang First release
PATH=/bin:/sbin:/usr/bin:/usr/sbin:/usr/local/bin:/usr/local/sbin:~/bin
export PATH

read -p "Please input an integer number: " number
i=0
s=0
while [ "$i" != "$number" ]
do
i=$(($i+1))
s=$(($s+$i))
done
echo "the result of ' 1+2+3+...$number' is ==> $s"
