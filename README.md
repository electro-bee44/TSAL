# TSAL
Tractive System Active Light(TSAL)

The TSAL has a red light, flashing continuously with a frequency between 2 Hz and 5 Hz, active if and only if the LVS is active and the voltage across DC-link capacitors exceeds
- 60 VDC or 25 VAC Root Mean Square (RMS)
- Half the nominal TS voltage whichever is lower

The TSAL itself has a green light, continuously on, active if and only if the LVS is active and ALL of the following conditions are true:
- All AIRs are opened.
- The pre-charge relay, is opened.
- The voltage at the vehicle side of the AIRs inside the TSAC does not exceed 60 VDC or 25 VAC RMS
