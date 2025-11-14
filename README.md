# SLWF-01pro-AUX-AC-Firmware
Esphome Yaml entry for SLWF-01pro (v1.1) for operating an AUX AC unit.

Mostly taken from https://github.com/GrKoR/esphome_aux_ac_component
Wanted to publicize my version for people looking to get their SLWF-01pro modules working with AUX AC units. 
Originally had a Mr. Cool unit with the stock firmware of the SLWF-01pro v1.1, but that unit died and I replaced it with the cheapest unit that I can find (Yitahome 120V 12k BTU). I was able to modify the above yaml and provide a working version for this specific esp module. The key is the pinout, tx and rx. I don't have a v2.1 to try unfortunately. 
This is where I got my unit which came with a generic broadcom wifi dongle. Simply replaced it and all is well:
https://www.yitahome.com/products/12000-btu-20-seer2-ductless-mini-split-air-conditioner-110v-p-7267.html?req_t=7267
