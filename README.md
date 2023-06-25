# Cargar nube de puntos

Funcion para cargar las nubes de puntos desde un archivo .txt con etiqueta



# CALCULO DE ANGULOS 
Calculo de angulo con dos vectores 


![Creacion de Mascara](https://github.com/Brayanjurado1325/Angulos-de-hojas/blob/main/Imagenes/1.png)


```ruby
def angulo(u,v):
  x = u.dot(v)
  y = np.linalg.norm(u)*np.linalg.norm(v)
  an = acos(x/y)   # Angulo en radianes
  a = math.degrees(an)  # Angulo en grados
  return a
```
Calculo de angulo usando 3 puntos

```ruby
def anguloFin(b,t,p):
  u= t - b
  v= p - b
  a = angulo(u,v)
  return a
```

# TRANSFORMAR NUBE DE PUNTOS



![Creacion de Mascara](https://github.com/Brayanjurado1325/Angulos-de-hojas/blob/main/Imagenes/puntosccescanos.png)



![Creacion de Mascara](https://github.com/Brayanjurado1325/Angulos-de-hojas/blob/main/Imagenes/)