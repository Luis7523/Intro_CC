# Intro_CC
#Crear las f basicas para evaluar mapa logistico
#Creado: 4-feb-2016
#Autor: Luis

r = 3.5
y0 = 0.1

print 'antes de for'


for counter in [0,1,2,3] :
	y1 = r * y0 * (1-y0)	
	y0 = y1	
	print y1
	
print 'despues de for'
