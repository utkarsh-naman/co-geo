# co-geo
Python library to solve 2d/3d coordinate geometry

[![utnamtte](https://img.shields.io/badge/PyPi-0.0.1-3670A0?style=for-the-badge&logoColor=ffdd54)](https://pypi.org/project/co-geo/)


**Installation**


    pip install co-geo

## Requirements
```python
pip install utnamtte

```

## Ways to import

Method 1

```python
import co-geo
print(co-geo.area_3d(...))
```


Method 2

```python
from co-geo import area
print(area(...))
```

Method 3

```python
from co-geo import area as xy
print(xy(...))
```

## Centroid_2d
```python
# Centroid_2d(x1, y1, x2, y2, x3, y3)
a = co-geo.Centroid_3d(0, 2,  3, 7, 6, 3)
print("x coordinate:",a.x)
print("y coordinate:",a.y)
```
```python
Output: 3
        4
```

## Centroid_3d
```python
# Centroid_3d(x1, y1, z1, x2, y2, z2, x3, y3, z3)
a = co-geo.Centroid_3d(0, 2, 11, 3, 7, 4, 6, 3, 6)
print("x coordinate:",a.x)
print("y coordinate:",a.y)
print("z coordinate:",a.z)

```
```python
Output: 3
        4
        7
```



## Square root

```python
print(tte("2√π11+3"))
```
```python
Output: 2*(math.sqrt(math.pi))*11+3
```
```python
# you can also use sqrt and √ under √ without brackets
print(tte("2√√sqrtπ11+3"))
```
```python
Output: 2*(math.sqrt(math.sqrt(math.sqrt(math.pi))))*11+3
```

## Mod or Absoulute
```python
print(tte("2|3-6|7+3"))
```
```python
Output: 2*(abs(3-6))*7+3
```

## Log
```python
print(tte("4ln11e"))
```
```python
Output: 4*(math.log(11))*math.e
```
```python
# you can also use log and ln of ln without brackets
print(tte("4lnlnlog1331π+3"))
```
```python
Output: 4*(math.log(math.log(math.log(1331))))*math.pi+3
```
```python
# use log to the desired base as follow
print(tte(f"log({number}, {base})"))
```

## Antilog
```python
print(tte(f"antilog({base}, {power})"))
```



Application of this library
**MATEX** is an application to input text mathematical expression and convert into python readable mathematical expression and output the result.
Also it can convert such mathematical expressions into **_Python_** and **_Java_** expressions.

This application was built using **Python** and **kivymd 0.104.2**.

🔗 Download the apk file from [here](https://drive.google.com/drive/folders/13NEsclz1rMhXaleFpfHcjPhmgV5ac7Gf)

▶️  [App tutorial here](https://youtu.be/_vezBiyNTOA)

