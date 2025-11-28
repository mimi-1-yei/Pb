# Pb
#Acá esta el parcial
a=input("dame un numero de 4 digitos : ")
digitos = set(a)
if len(digitos)!=4:
    print("no es valido")
elif len(digitos)==4:
  if a[0]=="0" or a[1]=="0" or a[2]=="0" or a[3]=="0":
     print("no es valido")
  elif a[0]!="0" or a[1]!="0" or a[2]!="0" or a[3]!="0":
    while a!=c:
      c=input("dame un numero de 4 digitos : ")
      digits = set(c)
      if len(digits)!=4:
        print("no es valido")
      elif len(digits)==4:
       if c[0]=="0" or c[1]=="0" or c[2]=="0" or c[3]=="0":
         print("no es valido")
       elif c[0]!="0" or c[1]!="0" or c[2]!="0" or c[3]!="0":
        if c==a:
         print("ese es")
        else:
         picas=0
         fijas=0
         for i in range(4):
          if c[i]==a[i]:
           fijas = fijas+1
          else:
           if c[i] in a:
            picas=picas+1
         print("mal")
         print("picas =", picas)
         print("fijas =",fijas)
