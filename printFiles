#!/bin/bash
usage()
{
cat << EOF
usage: $0 options

Use this script to print all files in target directory

OPTIONS:
   -h      Show this message
   -s      Server address
   -u      Username to login with
   -p      Passord to login with
   -d      File Directory
EOF
}

index=0
fileArray=
# for file in `ls`
# do
# 	fileArray[index]=filepath=`pwd`/$file
# done
fileArray=(`find . -type f -maxdepth 1 \( ! -iname ".*" \)`)
echo "files:"
echo ${fileArray[1]}
# /usr/bin/expect -c  "spawn ssh $username@joshua.dcs.warwick.ac.uk;\
#  expect \".*password:\"; \
# send \"$password\n \";\
# interact;"
