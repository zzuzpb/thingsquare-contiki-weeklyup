pull latest contiki repo with thingsquare, contiki is in https://github.com/panyongfeng/contiki , check README.md for more information


This is Thingsquare Mist, the Internet of Things software that lets
almost anything connect to the Internet

http://www.thingsquare.com/

The Thingsquare Mist code is divided into subdirectories:

* `apps/`     Thingsquare Mist applications
* `contiki/`  The Contiki OS
* `dev/`      Device drivers
* `examples/` Examples
* `platform/` Platform code
* `tools/`    Various tools


Added by Pan Yongfeng @20140205

Currently this is only for cc2538dk
* Makefile.cc2538 is updated
* some header files are updated to use updated version of contiki

the contiki is a symbol link to panyongfeng/contiki.git, which will be
sync with contiki-os/contiki.git weekly.

