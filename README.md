# K-09
while True :
	from hashlib import sha512
	v = input ("your text :")
	print ("—" *51)
	i = sha512(v.encode()).hexdigest()
	print (i)
	print ("—" *51)
