# -*- coding: cp1254 -*-

#Coded by iSo
#Website: www.ismailsaygili.com.tr && www.secwis.com
#Copyright 2013 ©

import os,_winreg
os.system("copy C:\\python27\\test.txt C:\\Users\\İsmail\\Desktop\\iso.txt")

key=_winreg.OpenKey(_winreg.HKEY_CURRENT_USER,"Software\\Microsoft\\Windows\\CurrentVersion\\Run",
0, _winreg.KEY_ALL_ACCESS)

_winreg.SetValueEx(key, "iso", 0, _winreg.REG_SZ, "C:\\python27\python.exe "+ os.getcwdu() + "\\kopyala.py")

key.Close()
