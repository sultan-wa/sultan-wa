from komputasi import *

 #~~~~~~inisialisasi matrik kernel G~~~~~#
G = array([[1.,5.,5.*5.],\
           [1.,8.,8.*8.],\
           [1.,14.,14.*14.],\
           [1.,21.,21.*21.],\
           [1.,30.,30.*30.],\
           [1.,36.,36.*36.],\
           [1.,45.,45.*45.],\
           [1.,60.,60.*60.]])
print G

  #~~~~~~inisialisasi vektor d~~~~~#
d = array([[21.75],\
           [22.68],\
           [25.62],\
           [30.87],\
           [40.5],\
           [48.72],\
           [63.75],\
           [96]])
print d
   #~~~~~~proses inversi~~~~~#
print inversi (G,d)
