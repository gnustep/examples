#   GNUmakefile: makefile for Finger.app
#
#   Copyright (C) 2000 Free Software Foundation, Inc.
#
#   Author:  Nicola Pero <n.pero@mi.flashnet.it>
#   Date: 2000
#   
#   This file is part of GNUstep.
#   
#   This program is free software; you can redistribute it and/or modify
#   it under the terms of the GNU General Public License as published by
#   the Free Software Foundation; either version 2 of the License, or
#   (at your option) any later version.
#   
#   This program is distributed in the hope that it will be useful,
#   but WITHOUT ANY WARRANTY; without even the implied warranty of
#   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#   GNU General Public License for more details.
#   
#   You should have received a copy of the GNU General Public License
#   along with this program; if not, write to the Free Software
#   Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA. */

include $(GNUSTEP_MAKEFILES)/common.make

APP_NAME = Finger
Finger_OBJC_FILES = \
  main.m \
  Controller.m \
  FingerWindow.m \
  PreferencesController.m \
  TrivialTextView.m
Finger_OBJC_PRECOMPILED_HEADERS = \
  FingerIncludeAll.h
Finger_HEADERS = \
  Finger.h \
  Controller.h \
  FingerWindow.h \
  PreferencesController.h \
  TrivialTextView.h 
Finger_RESOURCE_FILES = \
  finger.tiff \
  traceroute.tiff \
  ping.tiff \
  stop.tiff \
  whois.tiff \
  finger32.tiff \
  traceroute32.tiff \
  ping32.tiff \
  stop32.tiff \
  whois32.tiff

Finger_APPLICATION_ICON = finger.tiff

include $(GNUSTEP_MAKEFILES)/application.make

