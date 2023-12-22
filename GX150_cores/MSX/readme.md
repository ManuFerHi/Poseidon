https://github.com/DeMistified/MSX_deMiSTified

# OneChipMSX para [deMISTified Boards](https://github.com/DeMistified)

# Forked from MiST developer Git: (https://github.com/mist-devel/MSX_MiST)

### Placas soportadas: 
-Poseidon-ep4cgx150, Poseidon-10LC55, Neptuno DeMiSTified.

### Características:
- Basado en [KdL's version](https://gnogni.altervista.org/)
- Normal/Turbo CPU speed
- 2 MB/ 4MB RAM Interna
- Varias extensiones en Slot 1 y Slot 2
- SCART/VGA outputs
- YPbPr output
- Sonido i2s
- SD-Card Soporte directo MSX-DOS

### Uso:

El core en caso de usar una SD exlcusiva, requiere de una tarjeta SD formateada para FAT16 y el primer archivo en el directorio raíz debe ser el BIOS de MSX. Sin embargo, si no es conveniente utilizar una tarjeta separada, también se puede utilizar una tarjeta SD virtual en forma de archivo MSX.VHD o cualquier otro que se puede cargar desde el directorio raíz o de cualquier directorio de su tarjeta SD principal. Para preparar el almacenamiento, consulte el [sitio de KdL](https://gnogni.altervista.org/), especialmente OCM-Extra Pack, que tiene el BIOS y la utilidad SDCreate. O puede buscar/solicitar un archivo .vhd en [Atari-Forum](http://www.atari-forum.com/viewtopic.php?f=115&t=30889).

### Descargue binarios precompilados y ROM del sistema:
[poseidon]([https://github.com/mist-devel/mist-binaries/tree/master/cores/msx](https://github.com/ManuFerHi/Poseidon)). Copiar el fichero .rbf a la raíz de la SD card dependiendo de la FPGA instalada en la Placa Poseidon on en las releases de este git.
