Part 2 - ADC
1. You can set the bit resolutions to 12 bits, 10 bits, 8 bits or 6 bits.
Depending on the channel, the 12 bit resolution sampling rate in the fast channels
is 5.33 or 4.21 slow channels. For the 10 bit resolution the sampling rate is 6.15 in
the fast channel and 4.71 in the slow channel. For the 8 bit resolution the sampling
rate is 7.27 or the 5.33 in the slow channel. For the 6 bit resolution the sampling 
rate is 8.88 in the fast channel or 6.15 in the slow channel. This information was found 
under section 6.3.21 "Analog to Digital Converter Characteristics"/ Table 81 "ADC 
characteristics".

2.A voltage divider circuit is necessary because the photodiode acts like a current source 
in parallel with a diode. The resistor is needed to translate the current that is produced into a readable 
and consistent voltage since the resistor is of fixed value (vs the phtotdiode can produce varying
current based on light exposure).

Part 3 - DAC

1. The best resolution for DAC is 12 bits, so 2^12 - 4096. Using the equation, V_out - 9/4096(V_ref).

2. Lower sampling rates makes the quality of the output waveform a little fuzzy and not nearly as accurate
as using a higher samplign rate. Sawtooth waves sound louder than both sin and sqaure waves, but the 
square waves sounded a little more high pitched compared to the sine and sawtooth waves. A capacitor is needed
for the sake of not blowing up the headphones that are attached to the TRRS component. The capacitor can
block DC voltage + filter out lower, fuzzy frequencies.

 
