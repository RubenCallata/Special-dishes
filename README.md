print("special dishes")
verduras={"cebolla":5,"kion":45,"aji limo":485,"perejil":56,"lechuga":48,"pimiento":56}
tuberculos={"papa":91,"camote":74,"oca":35,"yuca":23,"mashua":46}
carnes={"res":50,"pescado":20,"pollo":15,"chancho":10,"conejo":30} 
otros={"sal":6,"mayonesa":1,"siyao":5,"huevo":6}

ingrediente=str(input("verduras:"))
for i in verduras.keys():
  if ingrediente in verduras:
    print{verduras[ingrediente]}
    ingrediente=str(input("verduras:"))
  elif ingrediente!=verduras.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      verduras.update({producto:costo})

ingrediente=str(input("tuberculos:"))
for i in tuberculos.keys():
  if ingrediente in tuberculos:
    print{tuberculos[ingrediente]}
    ingrediente=str(input("tuberculos:"))
  elif ingrediente!=tuberculos.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      tuberculos.update({producto:costo})

ingrediente=str(input("carnes:"))
for i in carnes.keys():
  if ingrediente in carnes:
    print{carnes[ingrediente]}
    ingrediente=str(input("carnes:"))
  elif ingrediente!=carnes.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      carnes.update({producto:costo})
      
ingrediente=str(input("otros:"))
for i in otros.keys():
  if ingrediente in otros:
    print{otros[ingrediente]}
    ingrediente=str(input("otros:"))
  elif ingrediente!=otros.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      otros.update({producto:costo})
