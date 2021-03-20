# astr-302-w21-project: Stargaze Assist
This program takes in inputs of your location in latitude and longitude and your date/time.
It returns a list of objects with relevent information that are ordered (approximately) by visibility and are within a circle directly above you, where the angle that forms the circle and the number of objects shown are dependent on a slider.
This is done by contacting the SDSS to download the objects visible in the sky from your location (in practice only ~500000) then sorting through the returned table to satisfy the slider's value, as well as the astropy module to take care of the tedious geometry inherent to this task.

While this is slightly impractical, I believe it demonstrates a working knowledge of the targeted concepts.
I will now fall into a deep slumber plagued by nightmares of red text.
