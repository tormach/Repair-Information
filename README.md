## Purpose
Tormach believes in your right to repair your machine after it has left the warranty period. 
Our machines are built for the long-term and failed components should not be a barrier to repairing issues as they come up.

This repository is intended as a long term source of information on all products we sell, even after they are no longer being manufactured new. 
We maintain it on a best-effort basis, so please let us know if we are missing information on a product you have.

If you need support on a product that is still under warranty, please contact our technicians at [https://tormach.com/support](https://tormach.com/support)

## :warning: Caution! :warning:

Items in this repository are intended for people familiar with component level repair of electronics, 
VFD programming, and microcontroller work. It is 100% possible to unintentionally brick parts of your Tormach machine (for example, by flashing 
VFD parameters intended for a different machine). 

Please use these resources carefully and if you are not sure how to use them please reach out to one of the indepenent repair technicians who work on Tormach machines.

## Index
The general structure of this repository is as follows:

* [Manuals and Technical Documents](Manuals/) - Service manuals and usage instructions for EOL Tormach products. 
* [Schematics](Schematics/) - Schematics of PCBs used in Tormach machines. Intended to facilitate board level repairs by skilled technicians.
* [Firmware](Firmware/) - Firmware used on MCUs on Tormach control boards. Intended to allow replacement and reflashing of MCU chips that have been damaged.
* [Parameter Files](Parameter_Files/) - Programming files for motor controllers used in Tormach machines. **Use extreme caution** - just because two machines use the same model of VFD does **not** mean they can share parameter files.
* [Whitepapers](Whitepapers/) - When Tormach makes an engineering decision that is particularly important to us, we often write a whitepaper explaining the rational that went into the decision. We release those here in hopes that they will be helpful to others in the maker community.

## Disclaimer
Tormach provides this information because we strongly believe that the end of a warranty should never spell death for a product. 
Component level repair of PCBs, reflashing PIC chips and modifying VFDs all require domain specific knowledge. Please reach out on 
one of our user groups if you are unsure how to proceed with a repair. 