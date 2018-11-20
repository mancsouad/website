#!/usr/bin/env bash

cd /home/vincent/website
while true ; do git pull ; sleep 10; cp /home/vincent/website/* /home/vincent/public_html/ ; done
