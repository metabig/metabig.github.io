---
layout: post
title:  "Firma Digital"
date:   2021-09-02 18:00:00 +0100
image:  12.jpg
---
# Firma Digital
Se necesita verificar que la firma es auténtica, es decir, que ha firmado realmente la persona que dice 
que ha firmado. Se firma con la clave privada y autenticamos con la clave pública.
- La idea de clave privada/pública de la criptografía asimétrica también se usa para la firma digital pero de forma inversa
- Si U quiere firmar un mensaje/documento M, simplemente 
aplica el algoritmo E con su clave privada de forma que el 
mensaje firmado es S = E<sub>SKu</sub>(M)
- Para verificar que el que ha firmado es realmente U, 
cualquier usuario puede aplicar el algoritmo de 
desencriptación usando la clave publica de U sobre el 
mensaje cifrado y comparar el resultado con el mensaje no 
cifrado, es decir verificar que D<sub>PKu</sub>(S) = M
