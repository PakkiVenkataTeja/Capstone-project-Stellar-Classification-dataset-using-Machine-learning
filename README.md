# Capstone-project-Stellar-Classification-dataset-using-Machine-learning


Context<br>

In astronomy, stellar classification is the classification of stars based on their spectral characteristics. The classification scheme of galaxies and stars is one of the most fundamental in astronomy. The early cataloguing of stars and their distribution in the sky has led to the understanding that they make up our own galaxy and, following the distinction that Andromeda was a separate galaxy to our own, numerous galaxies began to be surveyed as more powerful telescopes were built. This datasat aims to classificate stars, galaxies based on their spectral characteristics.

<br>Content

The data consists of  81,039 observations of space taken by the SDSS (Sloan Digital Sky Survey). Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star or galaxy


1. obj_ID= Object identifier, the unique value that identifies the object in the image catalog used by the CAS

2. alpha= Right Ascension angle (at J2000 epoch)

3. delta Declination angle (at J2000 epoch)

4. u Ultraviolet filter in the photometric system

5. g Green filter in the photometric system

6. r Red filter in the photometric system

7. i Near Infrared filter in the photometric system

8. z Infrared filter in the photometric system

9. run ID Run Number used to identify the specific scan

10. rereun_ID= Rerun Number to specify how the image was processed

11. cam_col Camera column to identify the scanline within the run

12. field JD Field number to identify each field

13. s spec_obj ID Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)

14. class object class (galaxy or star object)

15. redshift redshift value based on the increase in wavelength

16. plate plate ID: identifies each plate in SDSS

17. MJD-Modified Jullan Date, used to indicate when a given piece of SDSS data was taken

18. fiber JD fiber ID that identifies the fiber that pointed the right at the focul plane in each observation
