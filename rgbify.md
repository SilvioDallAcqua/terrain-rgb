The use of rgbify produces an error : densify_pts musst be at least 2
![30](./images/30.png)

We can workaround this error by edition the offending file mbtiler.py
![40](./images/40.png)
In the function _make_tiles change the default of densify_pts=0 to densify_pts=21
