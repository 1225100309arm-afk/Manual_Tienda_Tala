#  Tienda Talavera — Artesanías de Dolores Hidalgo 

---




###  
 **Rojo (terminal, `flutter test test/dominio_test.dart`):** `porcentaje()` sin `+ 50` trunca en lugar de redondear. Espera 1000 y sale 999.
![R2 rojo](capturas/R02_dinero_rojo.jpg)

con `(centavos * pct + 50) ~/ 100` redondea al centavo. 61/61.
![R2 verde](capturas/R02_dinero_verde.jpg)

### 
![R3 rojo](capturas/R03_carrito_rojo.jpg)

 con `>=` el envío es gratis desde $800. 61/61.
![R3 verde](capturas/R03_carrito_verde.jpg)


 `if (n > 9) n -= 9;` el algoritmo de Luhn marca como inválidas tarjetas buenas.
![R5 rojo](capturas/R05_tarjeta_rojo.jpg)

con la resta de 9 vuelve a validar bien. 61/61.
![R5 verde](capturas/R05_tarjeta_verde.jpg)

---
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/e6b8b8a9-0c8d-4d58-bf1d-ab4931ea2f24" />

<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/81e478df-8f2a-4f5e-bee7-f54ac32eb00c" />

<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/df334717-15d1-4389-aa2e-43669ebeca9b" />

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/cb85dd5b-b462-43d6-ab11-a2687a897ae4" />


flutter pub get
flutter test
flutter run
flutter build apk --release
```
En Windows hay que activar el **Modo de desarrollador** (lo pide para los plugins).
El visor 3D se ve en el emulador; la realidad aumentada solo funciona en un teléfono con ARCore.


