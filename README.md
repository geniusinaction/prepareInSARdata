# prepareInSARdata

A set of Jupyter notebooks that are designed to help InSAR neophytes prepare their data for modeling. As developed for the 2020 <a href="https://www.unavco.org/">UNAVCO</a> short course, <a href="https://www.unavco.org/education/professional-development/short-courses/2020/insar-theory-processing/insar-theory-processing.html">InSAR Processing and Time-Series Analysis for Geophysical Applications: InSAR Scientific Computing Environment (ISCE), ARIA Tools, and MintPy</a>.

full_data_downsaple_kite.ipynb is a one-stop shop for importing, cropping and downsampling ISCE-format interferograms, and can be tweaked to read any gdal-readable format, most likely. The other notebooks break the process down into steps (a bit less efficient).

Some dependencies:

<ul>
  <li><a href="https://pyrocko.org/docs/current/install/">pyrocko v2020.03.13</a> (and associated dependencies)</li>
  <li><a href="https://pyrocko.org/kite/docs/current/installation.html">kite v1.3.0</a> (and associated dependencies)</li>
  <li>numpy</li>
  <li>matplotlib</li>
  <li>gdal</li>
</ul>

