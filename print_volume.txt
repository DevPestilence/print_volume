Python 3.7.8 (tags/v3.7.8:4b47a5b6ba, Jun 28 2020, 08:53:46) [MSC v.1916 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> def print_volume (radius):
	pi = 3.141592653589793
	r = radius ** 3
	print(4 / 3 * (pi * r))

>>> print_volume(3)
113.09733552923254
>>> print_volume(8)
2144.660584850632
>>> print_volume(10)
4188.79020478639
>>> 