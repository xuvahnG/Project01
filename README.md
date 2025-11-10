# Project01 ------------  [X-ray intensity monitor]
1.1 EXCECUTIVE SUMMARY
The proposed inline intensity monitor will consist of a series of interchangeable photo-diodes with transmission geometry.
A total of 8 diodes with different thickness will be used. The optimal absorption of 25%-75% will be reached throughout the range 1850 eV to 20000 eV. These will be built as a linear array and a single translation stage can be used to swap diode.
Each diode can be calibrated against a thick absolute X-ray intensity monitor placed behind the linear array of diodes.
1.2 PHYSICS BACKGROUND
If one is to compensate a measurement for each shot, approximately the same number of phonons should be used for that measurement as for the registered signal. This is true in general and is especially evident for the case discussed for the FemtoMAX beamline, which is when the measurement is photon-statistic limited.
To see the importance and relevance of this argument we can take the early experiments at LCLS where the flux is 10e10 phonons per pulse after the monochromator. In a XAS measurement it would, in principle be possible to get a S/N ratio of (10e10)1/2 =10e5 given by Poisson statistics. However this only includes the photon statistics and the pulse-to-pulse fluctuations are significantly larger. At LCLS, about 10e-4 of the photon flux were scattered from SiN foils and measured by photodiodes as an intensity monitor to compensate for pulse-to-pulse fluctuations. Hence only 106 photons were registered which means that the best possible S/N ratio in the intensity was 10e3 which means that the latter is the best achievable accuracy in a single-shot measurement.
1.3 DIODES
For the design we have investigated the AXUV36 photodiode from IRD. It is possible to have these diodes manufactured in a range of thicknesses. Data on the manufacturers homepage is shown for the 5 um thick model
http://www.ird-inc.com/axuvtransmission/axuvtrans.htmlOscillator specifications
The absorption can be easily calculated using the CXRO homepage or similar.
http://henke.lbl.gov/optical_constants/filter2.html
The diode has a 20 mm thickness
<img width="792" height="667" alt="image" src="https://github.com/user-attachments/assets/766bac14-5348-4cf6-985a-1792679b06fa" />
So that 8 diodes require a 200 mm travel stage to also allow for an “open position”
The transmission within the spectral range is shown in the figure below with tentative
thicknesses of the diodes.
<img width="908" height="615" alt="image" src="https://github.com/user-attachments/assets/4b7f4a2f-559c-40c5-a48d-281c9a923ff2" />
The scanning range with 25-75% transmission is shown for each diode,
Thickness um / Scan range (eV)
2 / 1850*-3550,    *with 20% transmission
5 / 2800-4900
10 / 3600-6300
20 /4600-8000
50 /6400-11000
100 /8100-13800
200 /10200-17500
500 /14000-20000
1.4 EVALUATION OF SATURATION
At the DDR review it was pointed out that short pulses may saturate a photodiode with low shunt impedance. The diode was illuminated by the femtosecond laser at 800 nm. The penetration depth is similar to that of 5 keV X-rays
Most tests were made with a bias of 160V and a 10 micrometer thick diode. (These diodes were rejected due to too low shunt impedance. The intensity was set to mimic the FemtoMAX flux
19 microampere current gives 5 nC charge per pulse at 4.25 KHz. 5 nC corresponds to 3·1010 phooelectrons which at 3.6 keV is 3·107 photons per pulse. A light intensity of 1.0 in the plot below corresponds to the diode current 19 microampere.
<img width="1055" height="824" alt="image" src="https://github.com/user-attachments/assets/a986fd39-cdab-4a37-a00b-f8015ec5993a" />
At 300 V the diode remains linear up to 2·10e11 photoelectrons but the charge amplifier stopped
working as this exceeds the specifications
