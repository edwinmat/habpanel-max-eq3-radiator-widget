# habpanel-max-eq3-radiator-widget
Adapted version of widget that is published in the widget gallery

Refer to the discussion on: https://community.openhab.org/t/custom-widget-max-eq-3-radiators/39651/

Note: like Achim I burned the CUL firmware to my MAX-Cube, so I have a similar chain: Homegear –-> Homematic --> Openhab

Changes made:
- The changes described in message 21 (see https://community.openhab.org/t/custom-widget-max-eq-3-radiators/39651/21):
  - Remove ```'%.1f' | sprintf:``` in the code
- Renaming of all control modes (these values came from the Paper UI Control section):
  - AUTOMATIC --> AUTO-MODE
  - MANUAL --> MANU-MODE
  - BOOST --> BOOST-MODE
  - VACATION --> PARTY-MODE (??)
