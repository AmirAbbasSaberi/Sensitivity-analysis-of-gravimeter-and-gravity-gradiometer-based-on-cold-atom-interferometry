# Sensitivity-analysis-of-gravimeter-and-gravity-gradiometer-based-on-cold-atom-interferometry
This is the repository of parts of Amir Abbas Saberi's senior thesis in the study of design theory and evaluation of noise type in quantum gravimeter and quantum gravity gradiometer devices in University of Tehran.

# Noise Assessment 

Inertial sensors play a key role in the world of geodesy and geophysics.In the field of geodesy and geophysics of positioning, measuring gravity in general, measuring the forces governing the nature of the earth, is of special importance.\cite{torge2023geodesy} Inertial sensors play an important role in this environment.The construction of these sensors is done with various methods, but one of the newest methods has attracted a lot of attention from users, is quantum sensors because of their very high and remarkable sensitivity.

Gravity is one of the most fundamental and weakest forces of nature that causes changes in the shape of the earth's surface, and its study is used in obtaining the elevation model of the earth (geoid), discovering mineral and oil resources, studying general relativity and, measure the gravitational constant, etc.

Among the devices that are used to study gravity, we can mention gravimeter and gravity gradiometer, each of which has its own advantages and disadvantages.The purpose of measurement of quantum gravimeter (gravimeter based on cold atom interfermetry) is to measure gravitational acceleration in absolute terms. In this case, other disturbing forces such as Corellius force, centrifugal force, etc. and seismic errors and various other noises participate in the measurement. For this reason, quantum gravimeter, whose structure consists of two quantum absolute gravimeters with similar conditions, which are separated by a baseline, avoids systematic error participation and common system noise.\cite{snadden1998measurement} with the difference that instead of measuring gravity itself, it measures the gravitational gradient. In addition to eliminating noises and systematic errors, since the gravitational gradient is the second derivative of the gravitational potential, it works better than the absolute value of gravity itself in the study of changes and geoid modeling and cartography. With all the interpretations that the systematic error and common noise are removed, the gradiometer is not free from noise, and noises contribute to it in common and uncommon ways.

![figure2](https://github.com/AmirAbbasSaberi/Sensitivity-analysis-of-gravimeter-and-gravity-gradiometer-based-on-cold-atom-interferometry/assets/132078806/546e8b47-80b8-4d04-a903-59bfcbeb16fc)


Knowing the type of noise of the system helps in correct and accurate estimation of the parameters and finally the gravity gradient. Gradiometers currently employing atomic interferometry can reach sensitivities as high as 15 E/Hz. Device sensitivities are constrained by the quantum projection noise.

Various methods are used to estimate the parameters. These methods can be called Bayesian estimation and direct least squares ellipse fitting.



There are different methods to study system noise, one of the most important methods to study system noise in geodesy is the variance component estimation (LS-VCE) method, in which the noise parameters in the system are obtained by the least squares method. To characterize the noise of the system, different scenarios are designed, which are estimated with LS-VCE, each of these scenarios and in the condition that the generated noise is Gaussian, the most likely scenario for the system is determined with maximum likelihood Method. 

![figure11](https://github.com/AmirAbbasSaberi/Sensitivity-analysis-of-gravimeter-and-gravity-gradiometer-based-on-cold-atom-interferometry/assets/132078806/7f5a1d4b-41d6-409c-8493-e1705077f180)

However, for accurate modeling of noise before estimation, tools such as power spectral density and allan variance are used. The purpose of this article is to assess the type of noises contributing to the gravity gradiometer based on cold atoms.

