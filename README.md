# Kodaikanal Solar Observatory (KoSO) Digital Archive
## Maintained By: Bibhuti Kumar Jha (https://bibhuraushan.github.io)

***
***
# White-light Data
## Observation Statistics can be found [here](wl.html)
***
## **Extending the sunspot area series from Kodaikanal Solar Observator**
***
### Jha B. K., Hegde M., Priyadarshi A., Mandal S., Ravindra B. and Banerjee D.
### [*Front. Astron. Space Sci. 9:1019751*](https://ui.adsabs.harvard.edu/abs/2022FrASS...919751J/abstract)
-------------------------------------------------------------------------------
**Abstract:**
  Kodaikanal Solar Observatory (KoSO) possesses one of world’s longest and
  homogeneous records of sunspot observations that span more than a century
  (1904–2017). Interestingly, these observations (originally recorded in
  photographic plates/films) were taken with the same setup over this entire
  time period which makes this data unique and best suitable for long-term solar
  variability studies. A large part of this data, between 1921–2011, were
  digitized earlier and a catalog containing the detected sunspot parameters
  (e.g., area and location) was published in Mandal et al. (2017). In this
  article, we extend the earlier catalog by including new sets of data between
  1904–1921 and 2011–2017. To this end, we digitize and calibrate these new
  datasets which include resolving the issue of random image orientation. We fix
  this by comparing the KoSO images with co-temporal data from Royal Greenwich
  Observatory. Following that, a semi-automated sunspot detection and automated
  umbra detection algorithm are implemented onto these calibrated images to
  detect sunspots and umbra. Additionally, during this catalog updation, we also
  filled data gaps in the existing KoSO sunspot catalog (1921–2011) by virtue of
  re-calibrating the “rouge” plates. This updated sunspot area series covering
  nearly 115 years (1904–2017) are being made available to the community and
  will be a unique source to study the long term variability of the Sun.

**Description:**
  Regular observations at the Kodaikanal observatory began in 1904 using a
  white-light telescope with a 10-cm aperture lens and a f/15 light beam.
  Between 1912 and 1917, the objective lens was changed several times and in
  1918, a 15-cm achromatic lens was installed. This newconfiguration produced a
  20.4cm size image of the Sun in the imageplane. Photographic plates were used
  to capture the image. The same telescope has been used since 1918 up until 2011
  to take regular white-light observation of the sun.
  
  We present observations from 1904 to 2017.
  
  For quarries, contact Dipankar Banerjee (dipu@iiap.res.in)

**Data Description**
 | Bytes | Format | Units      | Label     	| Explanations |
 |:--    | :---:  | :---      | :---      | :---        |    
 | 1-22  | A22    |---         | Time       |	Time of Observation |
 | 24-28 |  F5.1  | degree     | Latitude   | Latitude of Sunspot|
 | 30-34 |  F5.1  | degree     | Longitude  | Longitude of Sunspot|
 | 36-41 | F6.1   | microHem   | Spot Area  | Area of Sunspot in Millionth of hemisph.|
 | 43-49 | F7.1   | microHem  |Umbra Area    | Area of Umbra in Millionth of hemisph.|

--------------------------------------------------------------------------------
**History:**
Copied at https://kso.iiap.res.in/white_light and 
https://github.com/bibhuraushan/KoSoDigitalArchive

**References:**
***
1. **Paper I:**   Ravindra et al.,     2013A&A...550A..19R
2. **Paper II:**  Mandal et al.,   Paper II    2017A&A...601A.106M
3. **Paper III:** Jha et al.,      Paper III   2022FrASS...919751J
***

