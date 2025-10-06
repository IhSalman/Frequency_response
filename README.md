• Frequency Response

Both filters behave like low-pass filters — they smooth out rapid changes in the signal.

The 5-point filter allows more high-frequency components to pass (less smoothing).

The 9-point filter attenuates more high frequencies, resulting in stronger smoothing and a narrower main lobe.

• Pole–Zero Plots

Zeros are located on the unit circle and evenly spaced.

Poles are located at the origin (FIR property).

Increasing the number of zeros (longer filter) makes the filter’s frequency response sharper and more selective.


<img width="1004" height="748" alt="Screenshot 2025-10-06 213540" src="https://github.com/user-attachments/assets/460e526c-cf2c-451c-a4f1-46e32a767c25" />
<img width="1009" height="750" alt="Screenshot 2025-10-06 213532" src="https://github.com/user-attachments/assets/23bfdd2c-de7d-40f6-abb4-7675f697f3b4" />
<img width="2544" height="1351" alt="Screenshot 2025-10-06 213510" src="https://github.com/user-attachments/assets/e9517f76-c73b-47d1-96b1-97a0811dbee1" />




FIR vs IIR Filters

FIR (Finite Impulse Response):

Impulse response ends after a finite number of samples.

Always stable.

Can achieve linear phase (no phase distortion).

Example: Moving Average Filter.

IIR (Infinite Impulse Response):

Impulse response continues indefinitely due to feedback.

Can become unstable if not designed properly.

More computationally efficient (fewer coefficients needed).

Examples: Butterworth, Chebyshev filters.
