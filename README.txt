Add celtofar.py to your python main folder (most likely c:\Python27\)
use {import celtofar}
use {tofar(Temp in c)} to convert cel to far
use {tocel(Temp in f)} to convert far to cel

example:

import celtofar
x = raw_input("degrees in cel to convert to far: ")
y = celtofar.tofar(x)
print y
