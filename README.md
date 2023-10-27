# Efficient Evaluation of the Fourier Transform of Multipoint Correlation Functions
This bachelor thesis deals with transforming Green's functions from the imaginary time domain to the frequency domain. Green's functions and their Fourier transform are useful entities, due to being directly measurable as physical quantities like the spectral function or the susceptibility. Complex many-body interactions can be modelled using two-, three- and multi-point functions. 
Due to the analytic evaluation in frequency space being very costly in comparison to evaluation in time, efficient Fourier transform methods are needed. Several numerical Fourier transform methods are compared with one another and assessed in terms of accuracy and runtime. The methods were applied to fermionic two-point, fermionic three-point and bosonic three-point correlation functions for Hubbard and Anderson impurity models.
The main results of this work include the implementation of the exact representations of the correlation functions in frequency space, as well as several numerical methods for the Fourier transform. Especially for three-point functions, due to time-ordering and a resulting discontinuity, simpler approaches begin to fail, but the so-called SimplexQuad method yields more accurate and faster results than the other approaches by two orders of magnitude.

Contact: <br>
Markus Reichel <br>
mx.markus.rei@gmx.net <br>
https://seismic.myftp.biz <br>
