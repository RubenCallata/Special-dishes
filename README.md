
print("special dishes")
verduras={"cebolla":5,"kion":45,"aji limo":485,"perejil":56,"lechuga":48,"pimiento":56}
tuberculos={"papa":91,"camote":74,"oca":35,"yuca":23,"mashua":46}
carne={"Res":50,"pescado":20,"pollo":15,"chancho":10,"conejo":30} 
otros={"sal":6,"mayonesa":1,"siyao":5,"huevo":6}
ingrediente=str(input("verduras:"))
for i in verduras.keys():
  while ingrediente==i:
    print{verduras[ingrediente]}
    ingrediente=str(input("verduras:"))
for i in verduras.keys():
  if ingrediente!=i:
    print("¿que ingrediente es y cuanto cuesta?")
    nuevo_ingrediente=str(input("ingresar ingrediente:"))
    costo=float(input("cuanto cuesta:"))
    verduras.update({nuevo_ingrediente:costo})
    print(verduras)
