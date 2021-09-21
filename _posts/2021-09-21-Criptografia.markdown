---
layout: post
title:  "Criptografia"
date:   2021-09-02 18:00:00 +0100
image:  12.jpg
---

# Criptografia
Del griego krypto y grapho; oculta y escritura.

Se ocupa de las técnicas de cifrado o codificado destinadas a alterar la representación
lingüística de un mensaje con el fin de hacerlo ininteligible aunque te hagan Sniffing.


## Ataques
Evaesdrop, Insertion, Impersonation, Hijacking, Denial of Service.

## Protege
+ Directamente: Confidencialidad, Autenticación, Integridad.
+ Indirectamente: Acceso y disponibilidad.

## Algoritmos históricos
+ Grupos y rotación
+ Substitución
La encriptación y desencriptación es conocido, el secreto es la clave.

## Shannon best practices

Confusión y difusión como condición necesaria para un cifrado seguro y práctico.

### Confusión
La relación entre clave y mensaje tiene que ser diferente.

Si se cambia un solo bit de la clave, el mensaje cifrado debería cambiar completamente.

### Difusión
La relación entre el mensaje y el mensaje cifrado tiene que ser diferente.

## Tipos de criptografía
### Criptografia privada o simétrica
Origen y destino usan la misma clave secreta.

La única hasta 1976.

Usan métodos basados en cifrado en bloques y cifrado de flujo.

Se necesita el intercambio de la clave entre los dos extremos a través de un sistema
seguro.

Cifrado en bloques: Se define un grupo de bits, llamado bloque, que tiene una transformación 
invariante que solo depende de la clave.

+ One time Pad (OTP): La clave y el mensaje tienen el mismo tamaño y se hace un XOR. cypher xor key = message.
+ Data Encryption Standard(DES): Elaborado por IBM el 1976. Hace lo de Shannon. Clave de 56 bits + 8 de paridad.
Algoritmo conocido. El descifrado usa el mismo algoritmo. La permutación inical y la permutación final no son
criptográficamente significativas. Las 16 rondas F son todas idénticas. Función Feistel (Expansión, Mezcla, Sustitución,
Permutación). Sustitución y permutación -> Confusión y difusión. 2 a la 56 combinaciones.

### Criptografia pública o asimetrica




