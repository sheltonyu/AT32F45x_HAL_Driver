from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f45x_acc.c'),
os.path.join(src_path, 'at32f45x_adc.c'),
os.path.join(src_path, 'at32f45x_aes.c'),
os.path.join(src_path, 'at32f45x_can.c'),
os.path.join(src_path, 'at32f45x_crc.c'),
os.path.join(src_path, 'at32f45x_crm.c'),
os.path.join(src_path, 'at32f45x_dac.c'),
os.path.join(src_path, 'at32f45x_debug.c'),
os.path.join(src_path, 'at32f45x_dma.c'),
os.path.join(src_path, 'at32f45x_emac.c'),
os.path.join(src_path, 'at32f45x_ertc.c'),
os.path.join(src_path, 'at32f45x_exint.c'),
os.path.join(src_path, 'at32f45x_flash.c'),
os.path.join(src_path, 'at32f45x_gpio.c'),
os.path.join(src_path, 'at32f45x_i2c.c'),
os.path.join(src_path, 'at32f45x_misc.c'),
os.path.join(src_path, 'at32f45x_pwc.c'),
os.path.join(src_path, 'at32f45x_qspi.c'),
os.path.join(src_path, 'at32f45x_scfg.c'),
os.path.join(src_path, 'at32f45x_sdio.c'),
os.path.join(src_path, 'at32f45x_spi.c'),
os.path.join(src_path, 'at32f45x_tmr.c'),
os.path.join(src_path, 'at32f45x_trng.c'),
os.path.join(src_path, 'at32f45x_usart.c'),
os.path.join(src_path, 'at32f45x_usb.c'),
os.path.join(src_path, 'at32f45x_wdt.c'),
os.path.join(src_path, 'at32f45x_wwdt.c'),
os.path.join(src_path, 'at32f45x_xmc.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F45x_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
