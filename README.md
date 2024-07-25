Detailed Data Dictionary for space_decay.csv Dataset
1. CCSDS_OMM_VERS: Version of the CCSDS (Consultative Committee for Space Data Systems)
Orbital Mean-Elements Message standard, which specifies the format of the orbital data.
2. COMMENT: General remarks or annotations about the data, often indicating the source or nature
of the data (e.g., "GENERATED VIA SPACE-TRACK.ORG API").
3. CREATION_DATE: The date and time when the data was created or generated.
4. ORIGINATOR: The organization or entity that generated or provided the data (e.g., "18 SPCS" -
18th Space Control Squadron).
5. OBJECT_NAME: The name of the space object, such as the name of the satellite or the
designation of the debris (e.g., "ARIANE 42P+ DEB").
6. OBJECT_ID: A unique identifier for the object, typically including the year of launch and a
sequential identifier (e.g., "1992-072J").
7. CENTER_NAME: The central body around which the object orbits (e.g., "EARTH").
8. REF_FRAME: The reference frame used for the data, often indicating the coordinate system
(e.g., "TEME" - True Equator Mean Equinox).
9. TIME_SYSTEM: The time system used for the data (e.g., "UTC" - Coordinated Universal Time).
Detailed Data Dictionary for space_decay.csv Dataset
10. MEAN_ELEMENT_THEORY: The theoretical model used to compute mean elements of the
orbit (e.g., "SGP4" - Simplified General Perturbations model 4).
11. EPOCH: The reference date and time for the orbital elements, indicating when the elements
were valid.
12. MEAN_MOTION: The number of orbits the object completes in one day, measured in revolutions
per day.
13. ECCENTRICITY: A measure of the orbit's deviation from a perfect circle, with 0 indicating a
circular orbit and values closer to 1 indicating more elliptical orbits.
14. INCLINATION: The tilt of the object's orbit relative to Earth's equatorial plane, measured in
degrees.
15. RA_OF_ASC_NODE: The right ascension of the ascending node, measured in degrees,
indicating the location where the object crosses the equatorial plane from south to north.
16. ARG_OF_PERICENTER: The argument of perigee, measured in degrees, indicating the angle
from the ascending node to the perigee (the closest point in the orbit to Earth).
17. MEAN_ANOMALY: The mean anomaly, measured in degrees, representing the fraction of an
orbit's period that has elapsed since the object passed perigee.
18. EPHEMERIS_TYPE: The type of ephemeris (a table or data file providing the predicted positions

Detailed Data Dictionary for space_decay.csv Dataset
of astronomical objects), often indicating the source or method used to generate the data.
19. CLASSIFICATION_TYPE: The classification of the object, such as "U" for unclassified.
20. NORAD_CAT_ID: The unique NORAD (North American Aerospace Defense Command) catalog
number assigned to the object.
21. ELEMENT_SET_NO: The element set number, indicating the specific set of orbital elements for
the object.
22. REV_AT_EPOCH: The revolution number of the object at the time of the epoch, indicating how
many orbits the object has completed since launch.
23. BSTAR: The drag term used in orbital models, representing the effect of atmospheric drag on
the object.
24. MEAN_MOTION_DOT: The first derivative of the mean motion, representing the rate of change
of the mean motion over time.
25. MEAN_MOTION_DDOT: The second derivative of the mean motion, representing the rate of
change of the first derivative over time.
26. SEMIMAJOR_AXIS: The semi-major axis of the orbit, measured in kilometers, representing the
average distance from the center of the object to the center of the orbit.

Detailed Data Dictionary for space_decay.csv Dataset
27. PERIOD: The orbital period, measured in minutes, representing the time it takes for the object to
complete one orbit around Earth.
28. APOAPSIS: The apoapsis distance, measured in kilometers, representing the farthest point from
Earth in the object's orbit.
29. PERIAPSIS: The periapsis distance, measured in kilometers, representing the closest point to
Earth in the object's orbit.
30. OBJECT_TYPE: The type of object, such as a satellite or debris.
31. RCS_SIZE: The radar cross-section size of the object, indicating its detectability (e.g., "SMALL,"
"MEDIUM," "LARGE").
32. COUNTRY_CODE: The country code of the country that launched the object.
33. LAUNCH_DATE: The launch date of the object.
34. SITE: The launch site from where the object was launched.
35. DECAY_DATE: The date when the object decayed or re-entered the Earth's atmosphere (if
applicable).
36. FILE: An internal file identifier used for reference.

Detailed Data Dictionary for space_decay.csv Dataset
37. GP_ID: An internal identifier for the General Perturbations model used to predict the orbit.
38. TLE_LINE0: Line 0 of the Two-Line Element set (TLE), usually containing the object name.
39. TLE_LINE1: Line 1 of the TLE, containing specific orbital elements and other related data.
40. TLE_LINE2: Line 2 of the TLE, continuing from Line 1 with additional orbital elements.
