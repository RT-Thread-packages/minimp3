# RT-Thread building script for component

from building import *

cwd = GetCurrentDir()
src = Glob('*.c') + Glob('*.cpp')
CPPPATH = [cwd]

group = DefineGroup('minimp3', src, depend = ['PKG_USING_MINIMP3'], CPPPATH = CPPPATH)

Return('group')
