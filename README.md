<img width="882" height="463" alt="Image" src="https://github.com/user-attachments/assets/0170cc7d-9d21-484a-8caf-b212beb8580c" />
500 Bridge Abutment
The code generates the geometry, assign all attributes, runs LUSAS, and plots the deformed mesh.
Users can edit geometry inputs.
The MC model is adopted for soil behaviour.
Interfaces and joints are not included.

# Dimensions in meters (adjust these values as needed)
d = 12.0    # Distance of abutment from right side, 3-100\
t = 3.0     # Distance of slope toe from left side,1-100\
s = 5.0     # Distance of the abutment from slope crest,1-10\
w = 30.0    # Model width, should not be less than d+t+s+2, d+t+s+2,100\
h3 = 5      # upper part model height 2,100\
h4 = 3.5    # free part of the abutement length (less than h3-2), 1:h3-1\
h1 = 8.0    # Model left side depth, 1:h2\
h2 = 11.5   # Model Right side depth (not less than h1+2),h1:100\
f = 5.0     # distributed load projecion (less than d-2), minimum 1m\
b = 1.5     # Half-width of the abutment base 1-2m



