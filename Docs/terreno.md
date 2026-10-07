# Datos del terreno

- Fuente DEM: OpenTopography (dataset Copernicus GLO-30, 30 m)
- Extensión: lon -79.25 a -78.93, lat -1.57 a -1.25
- Heightmap: GIS/salinas_heightmap.raw, 1025 x 1025, 16 bits, byte order Windows (little-endian)
- Altura mínima real del recorte: 255.3 m
- Altura máxima real del recorte: 4516.2 m
- Escala usada en la exportación: 255 m (valor 0) a 4517 m (valor 65535)
- Rango vertical (Terrain Height en Unity): 4262 m
- Altura base del terreno (posición Y en Unity): 255 m
- Tamaño horizontal aproximado: 35600 m (este-oeste) x 35400 m (norte-sur)
- Tamaño de píxel: 0.0003125 grados (aprox. 35 m)
- Esquina noroeste del heightmap: lon -79.25, lat -1.25 (primera fila = norte, requiere Flip Vertically en Unity)
- Nota: el remuestreo a 1025 px suaviza los extremos unos pocos metros