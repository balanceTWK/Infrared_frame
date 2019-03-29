from building import *

cwd     = GetCurrentDir()
src     = []
path    = [cwd]

src += ['infrared.c']
src += ['drv_infrared.c']

src += ['nec_decoder.c']

group = DefineGroup('Infrared_frame', src, depend = ['PKG_USING_INFRARED'], CPPPATH = path)

Return('group')
