MiSa
Prochlorococcus
.txt = Optode
_data.csv = Solisense Data
_fit.csv = Solisense Fit

202210261049_PICO_caloxy_MiSa1444_445.txt

20221026 10:49 Project Pico Experiment caloxy SampleID Actinic Light in Solisense + Optode for LRC
All done with temperature control cuvette
Solisense Excitation Always 445 nmm confirmed with fit file.

Chlorophyll Raw Data From Turner
https://docs.google.com/spreadsheets/d/13mQm0B3siS65UuGjNdzvpHFomfuwn6aAg7dBoq1IqrM/edit#gid=0

Chl Script
C:\Users\msavoie\Campbell Lab Dropbox\Mireille Savoie\Pico\R\ChlTurnerPICO.Rmd



SySl
Synechococcus 4 strains
Chlorophyll Raw Data From Turner
https://docs.google.com/spreadsheets/d/13mQm0B3siS65UuGjNdzvpHFomfuwn6aAg7dBoq1IqrM/edit#gid=0

C:\Users\msavoie\Campbell Lab Dropbox\Mireille Savoie\Pico\R\ChlTurnerPICO.Rmd

SoliSense File
PICO_202204061316_caloxy_SySl1156_445_LL_data.csv

Project PICO; YYYYMMDDHHMM; experiment; caloxy SampleID, Actinic and Excitation Light 445 nm; LL means nothing

SySl confirmed excitatation nm to match actinic nm.

Need to tick Excitation nm in Software to ensure Excitation and Actinic are the same.
Can cross check by looking at actual saturation curves or sigmaPSII in the 'dark'; if sigmaPSII is different for 445 nm and 590 nm shows that excitation nm is set to match actinic.
Also check variable column LEDSel for digital 10000 code for which LED is active for excitation.

PICO_202204061316_caloxy_SySl1156_445_LL_data.csv


_data means raw Solisense Data
_fit means Solisense fit



MaBe

Max may have also done 590 actinic + 445 excitation
Think how to interpret this data combination.
445 nm directly excites PSII, so Fv is coming 'direct' from PSII.
590 excites through the PBSome, so charge separations are being driven by 590 nm.

MURIS_202112100932_MaBe3729_590_caloxy_noTC_refit_fit.csv
Project MURIS
YYYYMMDDHHMM
SampleID
Actinic and Excitation Wavelength are the same nm for Max
exp caloxy
noTC is no TC
refit means refit with updated softare
fit means fit.

202112100842_MURIS_caloxy_MaBe3729_AL590_Ex590_TC.txt
YYYYMMDDHHMM
Project MURIS
exp caloxy
SampleID MaBe3729
AL590 actinic
Ex590 excitation
TC temperature control
