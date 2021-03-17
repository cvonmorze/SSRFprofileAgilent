# SSRFprofileAgilent

This package consists of a custom pulse sequence for efficiently measuring the spatial and spectral profiles of spectral-spatial radiofrequency (SSRF) excitation
pulses on a Agilent MRI scanner ('profile1d_test.c'). Package also includes flyback SSRF waveforms for selective excitation of [1-13C]pyruvate and [1-13C]lactate
(at the same slice location), respectively, at 4.7T, as well as code for automatically setting SSRF pulse center frequencies based on real-time scanner feedback ('auto_cf_c13').

VNMRJ source code is available via the OpenVNMRJ project on github: https://github.com/OpenVNMRJ

Distributed under the terms of the GNU General Public License. 

The included pulse waveforms were designed using the Spectral-Spatial-RF-Pulse-Design toolbox authored by Peder Larson and Adam Kerr. 
https://github.com/LarsonLab/Spectral-Spatial-RF-Pulse-Design
