Changelog
---------

PyHamTools 0.5.4
================

11. January 2016

 * Bugfix: Callinfo.get_all(callsign, timestamp) did ignore timestamp
 * added unit test for the bug above
 * extended timeout for QRZ.com request to 10 seconds (sometimes a bit slow)
 * updated QRZ.com unit tests for fixture callsigns (XX1XX and XX2XX)


PyHamTools 0.5.3
================

30. December 2015

 * Updated DXCC entity name of ZL9 (arrl id 16) from Auckland & Campbell to "N.Z. Subantarctic Is." in countrymapping.json (tnx G0UKB)
 * Deleted "Auckland" (016) from countrymapping.json
 * corrected code example of latlong_to_locator() (tnx VE5ZX)

PyHamTools 0.5.2
================

14. April 2015

 * catching another bug related to QRZ.com sessions


PyHamTools 0.5.1
================

13. April 2015

 * improved handling of expired QRZ.com sessions


PyHamTools 0.5.0
================

5. April 2015

 * implemented QRZ.com interface into LookupLib [LookupLib]

 * changed and unified all output to Unicode

 * corrected Longitude to General Standard (-180...0° West, 0...180° East) [LookupLib]

 * improved callsign decoding alogrithm [CallInfo]

 * added special case to decode location of VK9 callsigns [CallInfo]

 * added handling of special callsigns which can't be decoded properly inside a separate callsign exception file (e.g. 7QAA) [CallInfo]

 * added ValueError when LOTW data from file contains too many errors [qsl]


PyHamTools 0.4.2
================

11. October 2014

 * added pyhamtools.qsl (get EQSL.cc and LOTW user lists)

PyHamTools 0.4.1
================

27. September 2014

 * short calls in different countries (e.g. 9H3A/C6A) are now decoded correctly

 * added pyhamtools.frequency

 * moved pyhamtools.utils.freq_to_band into pyhamtools.frequency

 * deprecated module pyhamtools.utils

PyHamTools 0.4.0
================

20. September 2014

 * Added module for locator based calculations (pyhamtools.locators)
