#!/bin/bash
 
openbox-session &
 
xset s 0 0
xset -dpms
 
xset dpms force off
 
while true
do
  killall chromium-browser
  rm -rf ~/.{config,cache}/chromium/
 
  # start browser in your web site: here, just plain old localhost
  # -test-type will ignore any warnings and 
  # --ignore-certificate-errors will allow you to kiosk any https-page without displaying certificate errors
  chromium-browser -test-type --ignore-certificate-errors --kiosk --no-first-run --incognito http://localhost/ &
 
  sleep 10
 
  while true
  do
    pgrep chromium-browse
    if [ "$?" -eq "1" ]
    then
         #here you could execute something that is supposed to happen after the browser was accidentally quit
    fi
    sleep 1
  done
 
  exit 0
done