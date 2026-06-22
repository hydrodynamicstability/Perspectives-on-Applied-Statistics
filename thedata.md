## Principles of My Statistical Practice

by Christopher Tong

UNDER CONSTRUCTION!!!

### Be relentlessly skeptical of the data.

- Question the capabilities and quality assurance of the measurement processes.  The precision of an instrument is *not* the number of digits on its digital display.

- Search restlessly for selection bias, confounding, and systematic errors.

- What data are missing or hidden, and why?

- What was the original purpose of the data collection?

---

“Do not fall in love with data.”

  - Michael Pidd (1999)

“Data, if it is of poor quality, becomes a pollutant to clear thinking and rational decisions.”

  - J. Stuart Hunter (1980)


“My experience with data analysis indicates to me that problems with the data themselves are usually more numerous and more serious than problems with methodology.”

  - John C. Bailar, III (1976)

“In data analysis, a crucial and often bungled decision is the choice of data to be investigated. It may pay to ignore a massive majority, if it is distorted by systematic errors.”

   - Peter J. Huber (2011)

From a list of common statistical problems:  "Putting too much faith in 'real' data.  All measurement contains instrument error, a host of assumptions about scale, and archiving idiosyncrasies."

  - Albert R. Boehm (1998)

"Many a study, launched on the ways of elegant statistical design, later boggled in execution, ends up with results to which the theory of probability can contribute little."

  - W. Edwards Deming (1965)

"Any fool can take data. It’s taking good data that counts.”

   - Attributed to Eugene Commins (who denied saying it).  Source: American Institute of Physics [oral history interview](https://www.aip.org/history-programs/niels-bohr-library/oral-histories/44803) of Allan Franklin by David Zierler, 12 May 2020.

###  An example from my consulting experience

"We once worked with an instrument that allowed the user to retrieve stored time series data with a choice of time-resolution.  Upon investigation, we found that the system was artificially interpolating data, and reporting values not actually measured, if the user chose a high resolution."

  - C. Tong (2019)

Here are more details.  I was working with colleagues interested in preclinical models of hypertension.  The instrument was a blood pressure transducer, surgically implanted in a rat.  It transmitted blood pressure telemetry data to a wireless receiver mounted on the rat's cage.  The device was proprietary, and the vendor would not explain to us how the data were being sampled.  After consulting with our Bioelectronics workshop, their working hypothesis was as follows.  The transducer consisted of a piston which moved in response to changes in the fluid pressure felt on the blood-facing end.  The shift in the transducer position would change the voltage of a circuit, triggering a blood presure reading.  Thus the original "data" (which is never seen by the user) is irregularly spaced in time, and stored internally.  The "data" output to the user consists of a time series interpolated onto a set of evenly spaced time points, whose "sampling frequency" was set by the user.

The bottom line is that if the user requested a high sampling rate, the "data" returned may well be completely illusory.  Regardless of the sampling rate, the system would only output interpolated, not "raw" data.  So there were limits as to how seriously to treat the "data" (we were interested in evidence of wave reflection, for example, which would require sufficient resolution to trace fine features of the blood pressure waveform).

### References

J. C. Bailar, III, 1976:  Bailar’s laws of data analysis. *Clinical Pharmacology and Therapeutics*, 20: 113-119.

A. R. Boehm, 1998:   How not to fool yourself with statistics.  *14th Conference on Probability and Statistics in the Atmospheric Sciences*, 11-16 January 1998, Phoenix, AZ.  American Meteorological Society.

W. E. Deming, 1965: Principles of professional statistical practice. Annals of Mathematical Statistics, 36: 1883-1900.

P. J. Huber, 2011:  *Data Analysis: What Can Be Learned from the Past 50 Years*. Wiley.

J. S. Hunter, 1980:  The national system of scientific measurement. *Science*, 210: 869-874.

M. Pidd, 1999:  Just modeling through: a rough guide to modeling. *Interfaces*, 29 (2): 118-132.

C. Tong, 2019: Statistical inference enables bad science; statistical thinking enables good science. *American Statistician*, 73, sup 1: 246-261.

---

#### Disclaimers

The content on this site was developed solely on my personal time. The views expressed are solely my own, and do not necessarily represent the views, policies, or opinions of my employer or any organization with which I am affiliated.

(c) 2026 by Christopher Tong, except for quoted material
