#!/usr/bin/env bash
# -*- coding: utf-8 -*-
# Author: graypawn (choi.pawn @gmail.com)
# Created: 2016-05-29

output=HDMI2
X=1920
Y=0

if (xrandr --listmonitors | grep $output 1>/dev/null); then
    xrandr --output $output --off
    echo $output turn off
else
    xrandr --output $output --auto --pos "$X"x"$Y"
    echo $output turn on
fi
