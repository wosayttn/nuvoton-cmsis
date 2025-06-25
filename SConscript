import os
from building import *

objs = []
cwd  = GetCurrentDir()

if GetDepend(['SOC_SERIES_MA35D1']) or GetDepend(['SOC_SERIES_M480']) or GetDepend(['SOC_SERIES_M032']):
    objs = objs + SConscript('m031_m480_ma35/SConscript')

if GetDepend(['SOC_SERIES_M460']) or GetDepend(['SOC_SERIES_M2354']):
    objs = objs + SConscript('m460_m2354/SConscript')

Return('objs')