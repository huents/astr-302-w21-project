# astr-302-w21-project
This program takes in imputs of your location in latitude and longitude and your date/time.
It returns a list of objects ordered (approximately) by visibility that are within a circle directly above you, where the angle that forms the circle and the number of objects shown is dependent on a slider.
This is done by contacting the SDSS to download the objects visible in the sky from your location (in practice only ~500000) then sorting through the returned table to satisfy the slider's value, as well as the astropy module to take care of the tedious geometry inherent to this task.
