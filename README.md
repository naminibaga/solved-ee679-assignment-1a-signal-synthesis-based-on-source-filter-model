Download Link: https://assignmentchef.com/product/solved-ee679-assignment-1a-signal-synthesis-based-on-source-filter-model
<br>
Note: You can use Python, Octave or Matlab/Scilab.  Make a single zipped folder that includes a pdf (with the solution for each question including method, code fragments, plots and discussion) and sound files. You can also include your code file itself (e.g. .py or .ipynb).

<ol>

 <li>Given the following specification for a single-formant resonator, obtain the transfer function of the filter H(z) from the relation between resonance frequency / bandwidth, and the pole angle / radius. Plot filter magnitude response (dB magnitude versus frequency) and impulse response.</li>

</ol>

F1 (formant) = 900 Hz

B1(bandwidth) = 200 Hz

Fs (sampling freq) = 16 kHz

<ol start="2">

 <li>Excite the above resonator (“filter”) with a periodic source excitation of F0 = 140 Hz. You can approximate the source signal by narrow-triangular pulse train. Compute the output of the source-filter system over the duration of 0.5 second using the difference equation implementation of the LTI system. Plot the time domain waveform over a few pitch periods so that you can observe waveform characteristics.  Play out the 0.5 sec duration sound and comment on the sound quality.</li>

 <li>Vary the parameters as indicated below and comment on the differences in waveform and sound quality for the different parameter combinations.</li>

</ol>

<ul>

 <li>F0 = 120 Hz, F1 = 300 Hz, B1 = 100 Hz</li>

 <li>F0 = 120 Hz, F1=1200 Hz, B1 = 200 Hz</li>

 <li>F0 = 180 Hz, F1 = 300 Hz, B1 = 100 Hz</li>

</ul>

<ol start="4">

 <li>In place of the simple single-resonance signal, synthesize the following more realistic vowel sounds at two distinct pitches (F0 = 120 Hz, F0 = 220 Hz). Keep the bandwidths constant at 100 Hz for all formants. Duration of sound: 0.5 sec</li>

</ol>

Vowel F1, F2, F3

/a/ 730, 1090, 2440

/i/ 270, 2290, 3010

/u/ 300, 870, 2240

(Optional:  Use glottal pulse shaping and lip radiation filtering. Add a small amount of aspiration noise and pitch jitter.)





