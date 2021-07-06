# exercise8

#transforming meters into other units of measurament

medida = float (input ('qual a medida em metros?   '))

cm = float (medida * 100)
mm = float (medida * 1000)
pes = float (medida * 0.3048)
km = float (medida * 0.001)
mil = float (medida * 0.000621371)
print ('{} metro(s) em centimetros é {}, em milimetros é {}, em pés é {}, em kilometros é {:.2f} e em milhas é {:.2f} ' .format (medida , cm , mm , pes , km , mil))
