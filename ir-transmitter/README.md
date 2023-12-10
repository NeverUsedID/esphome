# Simple IR Blaster example

# Broadlink converter
To convert Broadlink codes to ESP Home compatible IR-Commands use on Linux:

```
pip install irgen
irgen -i broadlink_base64 -d "JgBQAAABIo8TERQQFBAUEBQQFRAUEBQQFTMUNBQ0EzQTNRM1EzUTMxQ0FBEUMxQRFBAUEBUzFBAVEBM0ExITNBM1EzUTEBUzFAAE/QABI0YUAA0F" -o pronto
```
