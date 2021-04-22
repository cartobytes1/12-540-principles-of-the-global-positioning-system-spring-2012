---
course_id: 12-540-principles-of-the-global-positioning-system-spring-2012
layout: course_section
menu:
  leftnav:
    identifier: 7db57be82ce7e0cdb5293f5578c683b0
    name: Lecture Notes
    weight: 20
title: Lecture Notes
type: course
uid: 7db57be82ce7e0cdb5293f5578c683b0

---

| LEC # | TOPICS | NOTES, SUPPORTING FILES AND LINKS |
| --- | --- | --- |
| 1 | Overview of the aims of the class ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec1)) |  {{< br >}}{{< br >}} Class introduction and content {{< br >}}{{< br >}} [U.S. Coast Guard Navigation Center Website](http://www.navcen.uscg.gov/)  {{< br >}}[University NAVSTAR Consortium Website](http://www.unavco.org/)  {{< br >}}[SCIGN Data Portal Website](http://reason.scign.org/) {{< br >}}{{< br >}}  |
| 2 | Coordinate and time systems ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec2)) | Introduction to coordinate system definition and realization concentrating on geometric definitions  {{< br >}}[SCO Web: Control Networks](https://www.sco.wisc.edu/surveying/geodetic-standards-networks/)  {{< br >}}[National Geodetic Survey](http://www.ngs.noaa.gov/) |
| 3 | Potential fields and coordinate systems ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec3)) | Potential fields and coordinate systems. We also used some Matlab scripts in this lecture. The two programs are Harmonics.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/06127c1412829a04a86d7b3639e7a55c_Harmonics.m)), which plots low order harmonics and Sectorials.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/362ee9b75472ebc1eb10a8e090500a99_Sectorials.m)), which plots high order sectorial harmonics. Surface harmonic figure and code: SurfaceHarmonic.fig ([FIG](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/e74782efb6d7823992598c8cecb1d941_SurfaceHarmonic.fig)) and SurfaceHarmonic.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/10befe56ad0b681ade40ddd8a2fed793_SurfaceHarmonic.m))  {{< br >}}[Legendre Polynomial](http://mathworld.wolfram.com/LegendrePolynomial.html) |
| 4 | Coordinate types ([PDF - 1.7MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec4)) | Coordinate systems, rotation of the Earth, Geoid, Spherical trigonometry  {{< br >}}[International Earth Rotation and Reference Systems Service](http://www.iers.org/)  {{< br >}}Modeling of Nutation-Precession: Very long baseline interferometry results (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](http://geoweb.mit.edu/~tah/12.540/icd200cw1234.pdf))  {{< br >}}[Computation of Geoid99 Geoid Height](http://www.ngs.noaa.gov/cgi-bin/GEOID_STUFF/geoid99_prompt1.prl)  {{< br >}}[Spherical Trigonometry](http://mathworld.wolfram.com/SphericalTrigonometry.html) |
| 5 | GPS satellite orbits ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec5)) | GPS satellite orbits. The MATLAB program to compute eccentic and true anomalies is truea.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/d3f28a890aea301605f8e8b18f7309f6_truea.m))  {{< br >}}The GPS interface control document (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](http://geoweb.mit.edu/~tah/12.540/icd200cw1234.pdf))  {{< br >}}Unclassified (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF - 1.3MB](http://geoweb.mit.edu/~tah/12.540/icd200cw1234.Nav.pdf)) |
| 6 | GPS observables ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec6)) | Start analysis of GPS observables in form of carrier phase |
| 7 | Specifics of GPS signal ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec7)) | GPS codes on signals |
| 8 | Pseudorange measurements ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec8)) | Pseudorange and phase measurements. The data file displayed in class is etab.plt.dat ([DAT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/823d0630d8a32aad008ebca5e3dd37f4_etab.plt.dat))  {{< br >}}[TEQC—The Toolkit for GPS/GLONASS/Galileo/SBAS Data](http://www.unavco.org/facility/software/teqc/teqc.html)  {{< br >}}RINEX: The Receiver Independent Exchange Format Version 2 ([TXT](./resolveuid/7011abfcc38880524b44d32e07d31bc8)) |
| 9 | Range and phase data ([PDF - 1.3MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec9)) | The data files displayed in class are ASCII tab delimited files: etab.02tab ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/2403e4d6ff7cb3de215e5105c4d1dfb2_etab.02tab)) etab.07tab ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/54138f73072b6b0c476081d2e167343c_etab.07tab)) etab.11tab ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/8f08e64efe529dde33b1ab75ad546cd1_etab.11tab)) etab.26tab ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/f8ed916cdc9569f78de556d36ff0fb9f_etab.26tab)) etab.28tab ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/e136988dca3b91c52a9b22117bdfd8be_etab.28tab))  {{< br >}}The following files are based on 2008 homework: data from base station with approximate XYZ coordinates  {{< br >}}\-2197259.2644 -4811601.7696 3552341.4441 (m)  {{< br >}}Each file has a header line with column titles. All range and phase units are meters except as noted where range differences have been converted to L1 cycles  {{< br >}}base.02 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/98a6edf024700a71c4c18257d4356505_base.02)) base.04 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/8e567aba089c69239b2938534c8f4a2d_base.04)) base.05 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/9139fb4a0d35e8e4a8fc7da7037a9328_base.05)) base.09 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/475a95a58ee4f4f6cd16846c6e497637_base.09)) base.12 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/43fc10c41922cd8776e8d5c4a0ca3134_base.12)) base.17 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/782e7f9d995c4c0101de39655f7f8a2c_base.17)) base.28 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/8026c3f79c88291b020f46f6faddbebc_base.28)) base.29 ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/9f39ad6f8687251171376c7d85c14529_base.29))  {{< br >}}The site coordinates are in the rinex header shown in Lec #8  {{< br >}}Sources of GPS data (main archives)  {{< br >}}[SOPAC](http://sopac.ucsd.edu/)  {{< br >}}[CDDIS](http://cddis.gsfc.nasa.gov/)  {{< br >}}[NGS/CORS](http://www.ngs.noaa.gov/CORS/)  {{< br >}}[UNAVCO](http://www.unavco.org/data/data.html) |
| 10 | Estimation: introduction ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec10)) | Start estimation looking a parametric estimation methods  {{< br >}}[Data Analysis for Process Modeling](http://www.itl.nist.gov/div898/handbook/pmd/section4/pmd4.htm)  {{< br >}}[Least Squares Parameter Estimation (Regression Analysis)](http://reliawiki.org/index.php/Least_Squares) {{< br >}}{{< br >}} histograms.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/5477bd9535bb040497f3844cf45c01a4_histograms.m)) generates histogram plots {{< br >}}{{< br >}}  |
| 11 | Statistical approach to estimation ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec11)) | Continue estimation now examining it from a statistical point of view |
| 12 | Estimation: correlations ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec12)) | Statistical description of process noise in parameter values. The MATLAB program fogm.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/6a5d899928c34c940ba3c9b450cbb26c_fogm.m)) generates first-order Gauss Markov processes. (Note since the random number generator is not initialized, your results will differ from those in the class notes (Signal processing tool box is needed for the PSD calculation). FlickerNoise.m ([M](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/85d40911dfd241ee6144009f5aa4e26b_FlickerNoise.m)) implements flckernoise model through PSD->Covarinace Matrix->eigenvectors and values |
| 13 | Estimation ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec13)) | Kalman filter approach to estimation |
| 14 | Propagation medium: propagation ([PDF - 2.3MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec14)) | Timing in GPS. Examine clock estimation  {{< br >}}[IGS Clock Products Working Group](https://www.nrl.navy.mil/ssdd/research-activities/8150/igs)  {{< br >}}[IGS Time Scale](https://www.researchgate.net/publication/3918247_Developing_an_IGS_time_scale) |
| 15 | Propagation medium: neutral atmosphere ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec15)) | Tropospheric delay estimation  {{< br >}}[The Height of the Tropopause](http://www-das.uwyo.edu/~geerts/cwx/notes/chap01/tropo.html)  {{< br >}}Effects of the Troposheric Mapping Function on Space Geodetic Data (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF - 1.0MB](http://gauss.gge.unb.ca/papers.pdf/igs97tropo.pdf))  {{< br >}}[Index of /DELAY](http://ggosatm.hg.tuwien.ac.at/DELAY/) |
| 16 | Propagation: ionospheric delay ([PDF - 1MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec16)) | Ionospheric delays  {{< br >}}[National Geophysical Data Center](http://www.ngdc.noaa.gov/stp/SOLAR/ftpcalcium.html)  {{< br >}}Data file (Year Month Day SunSpot number)  {{< br >}}[RIDAILY (1811-2012/04)](http://geoweb.mit.edu/~tah/12.540/RIDAILY_120407.txt) |
| 17 | Basic antenna operation ([PDF - 1.7MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec17)) | Antennas and calibrations  {{< br >}}[NGS/Antenna Calibrations](http://www.ngs.noaa.gov:80/ANTCAL/) |
| 18 | Mathematical models in GPS ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec18)) | Class starts development of mathematical models needed for precise GPS positioning. In this class we look at solid-Earth tides, ocean-tidal loading and other types of loading effects. The following Fortran source code was discussed in the lecture earth\_tide.f ([F](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/119a1db7a43370926adb6236db8768de_earth_tide.f)) and gst\_jd.f ([F](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/3e1312cf311b463fb1e654f2fc910558_gst_jd.f)) |
| 19 | GPS models and processing ([PDF - 1.4MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec19)) | Models: Rank deficiencies, ambiguity resolution and differencing methods |
| 20 | Processing software ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec20)) | Processing software:  {{< br >}}[GAMIT/GLOBK Web Tutorial](http://geoweb.mit.edu/~simon/gtgk/tutorial/Index.html) |
| 21 | GPS groups/IGS ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec21)) |  {{< br >}}{{< br >}} GPS data availability and site locations  {{< br >}}[UNAVCO](http://www.unavco.org/data/data.html)  {{< br >}}[International GNSS Service](http://gpsworld.com/tag/international-gnss-service/)  {{< br >}}International GNSS Service—All world map ([PNG](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/8fdac9229c4844259c4834dc2c293dd6_all_world.png)) {{< br >}}{{< br >}} Networks  {{< br >}}[SCIGN](http://www.scign.org/)  {{< br >}}[UNAVCO](http://www.unavco.org/data/data.html)  {{< br >}}[NGS/CORS](http://www.ngs.noaa.gov/CORS/)  {{< br >}}[Bay Area Regional Deformation Network](https://seismo.berkeley.edu/bard/)  {{< br >}}[Pacific Northwest Geodetic Array](http://www.panga.cwu.edu/) {{< br >}}{{< br >}} Results  {{< br >}}[Permanent GPS Site Arrays](http://sopac.ucsd.edu/)  {{< br >}}[GPS Time Series](http://sideshow.jpl.nasa.gov/mbh/series.html)  {{< br >}}[SCIGN Data Portal](http://reason.scign.org)  {{< br >}}[GPS Explorer](http://geoapp03.ucsd.edu/gridsphere/gridsphere)  {{< br >}}[UNAVCO](http://www.unavco.org/data/data.html) {{< br >}}{{< br >}}  |
| 22 | Kinematic GPS ([PDF]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec22)) | Kinematic GPS processing and results from experiment earlier in semester  {{< br >}}Results from MIT survey  {{< br >}}track\_LC.out ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/f3790fe25d5106a0d54a780cd7f970e9_track_LC.out))  {{< br >}}track.NEU.rovr.LC ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/594b0826c0ac7adffe340fe0edcc0be5_track.NEU.rovr.LC))  {{< br >}}track.NEU.rovr.L1+L2 ([TXT](./resolveuid/adb820ca15496d7ae116d84a824ae963))   {{< br >}}{{< br >}} **Results from the 2010 MIT survey** {{< br >}}{{< br >}} TR02.sum ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/fb17f61e7d2e3ba5555bfb1162fe1364_TR02.sum)) TR02.out ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/7a9966fc19600b7a2be1d0b0a58629d3_TR02.out)) TR02.NEU.rovr.L1+L2 ([TXT](./resolveuid/c1d2a222013826d2b468d6da55c971aa)) TR02.NEU.rovr.LC ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/727bcf448e412c0f63125fddec4d86c3_TR02.NEU.rovr.LC))  {{< br >}}TR0p.sum ([TXT](/coursemedia/12-540-principles-of-the-global-positioning-system-spring-2012/fa022ac88deeac3eadfe2a40c739cebc_TR0p.sum)) TR0p.NEU.rovr.P1+P2 ([TXT](./resolveuid/f7c410edbea672c589d1296fb63a0d02)) |
| 23 | Applications, High-rate GPS results, and Tools ([PDF - 6.4MB]({{< baseurl >}}/sections/lecture-notes/mit12_540s12_lec23)) | Applications to tectonic problems  {{< br >}}Tools used to generate some of the figures  {{< br >}}[GAMIT/GLOBK MATLAB Tools](http://www-gpsg.mit.edu/~tah/GGMatlab)