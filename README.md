# utnamgeo
Python library to solve 2d/3d coordinate geometry

[![utnamtte](https://img.shields.io/badge/PyPi-0.0.1-3670A0?style=for-the-badge&logoColor=ffdd54)](https://pypi.org/project/utnamgeo/)


**Installation**


    pip install utnamgeo

## ⭐ Requirements
```python
pip install utnamtte

```

## ⭐Ways to import

Method 1

```python
import utnamgeo
print(utnamgeo.area_3d(...))
```


Method 2

```python
from utnamgeo import area_3d
print(area_3d(...))
```

Method 3

```python
from utnamgeo import area_3d as xy
print(xy(...))
```

Method 4
```python
from utnamgeo import *
print(area_3d(...))
```

---------------------------------------------------------

# ⭐ Useful functions

## area_2d
## area_3d
## fop
## intersect
## iscollinear
## iscollinear_3d
## perimeter_2d
## perimeter_3d


---------------------------------------------------------

# ⭐ Centres

## Centroid_2d
```python
# Centroid_2d(x1, y1, x2, y2, x3, y3)
a = utnamgeo.Centroid_2d(0, 2,  3, 7, 6, 3)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
```
```python
Output: 
x coordinate: 3

y coordinate: 4
```

## Centroid_3d
```python
# Centroid_3d(x1, y1, z1, x2, y2, z2, x3, y3, z3)
a = utnamgeo.Centroid_3d(0, 2, 11, 3, 7, 4, 6, 3, 6)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
print("z coordinate:", a.z)

```
```python
Output:
x coordinate: 3

y coordinate: 4

z coordinate: 7
```

## Circumcentre_2d
```python
# Circumcentre_2d(x1, y1, x2, y2, x3, y3)
a = utnamgeo.Circumcentre_2d(2, -5, 2, 7, 14, -5)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
```
```python
Output: 
x coordinate:  8

y coordinate:  1
```

## Circumcentre_3d
```python
# Circumcentre_3d(x1, y1, z1, x2, y2, z2, x3, y3, z3)
a = utnamgeo.Circumcentre_3d(2, -5, -3, 2, 7, -3, 14, -5, 6)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
print("z coordinate:", a.z)

```
```python
Output: 
x coordinate:  8

y coordinate:  1

z coordinate:  5
```

## Excentre_2d
```python
# Excentre_2d(x1, y1, x2, y2, x3, y3)
a = utnamgeo.Excentre_2d(2, -5, 2, 7, 14, -5)
print("x coordinate:", a.xa)
print("y coordinate:", a.ya)
```
```python
Output: 
x coordinate:  5.11625...

y coordinate: -1.1046...  
```

## Excentre_3d
```python
# Excentre_3d(x1, y1, z1, x2, y2, z2, x3, y3, z3)
a = utnamgeo.Excentre_3d(2, -5, -3, 2, 7, -3, 14, -5, 6)
print("x coordinate:", a.xa)
print("y coordinate:", a.ya)
print("z coordinate:", a.za)

```
```python
Output: 
x coordinate:  5.11625...

y coordinate: -1.1046...

z coordinate: -0.6628...  
```

## Incentre_2d
```python
# Incentre_2d(x1, y1, x2, y2, x3, y3)
a = utnamgeo.Incentre_2d(2,-5,2,7,14,-5)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
```
```python
Output:
x coordinate:  5.1162...

y coordinate: -1.1046...

z coordinate: -0.6628...
```
## Incentre_3d
```python
# Incentre_3d(x1, y1, z1, x2, y2, z2, x3, y3, z3)
a = utnamgeo.Incentre_3d(2, -5, -3, 2, 7, -3, 14, -5, 6)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
print("z coordinate:", a.z)
print("In-radius: ", a.radius)
```
```python
Output:
x coordinate:  5.1162...

y coordinate: -1.1046...

z coordinate: -0.6628...

In-radius:     3.8953...
```

## Orthocentre_2d
```python
# Orthocentre_2d(x1, y1, x2, y2, x3, y3)
a = utnamgeo.Orthocentre_2d(2,5,2,8,14,5)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
```
```python
Output:
x coordinate: 2

y coordinate: 5
```
## Orthocentre_3d
```python
# Orthocentre_3d(x1, y1, z1, x2, y2, z2, x3, y3, z3)
a = utnamgeo.Orthocentre_3d(2, -5, -3, 2, 7, -3, 14, -5, 6)
print("x coordinate:", a.x)
print("y coordinate:", a.y)
print("z coordinate:", a.z)

```
```python
Output:
x coordinate: 2

y coordinate: -5

z coordinate: -3 
```


▶️  [Package's YouTube tutorial here](https://www.youtube.com/playlist?list=PLZchMekN22UmCqi9sCEEoAYBPsNvQrvBU)

