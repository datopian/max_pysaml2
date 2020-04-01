This module provides some quick monkey-patches to allow the pysaml2 library to 
work with MAX.gov which uses a non-standard saml2 implementation.

This is the python 2.7 version which relies on pysaml2@4.9.0

To use, install this module and the pysaml2 module in your project. Then load
pysaml2 followed by this module in your project: pysaml2 will now have the 
appropriate patches for use with MAX.gov

See `example.py` for an example of how to use this in your project.
