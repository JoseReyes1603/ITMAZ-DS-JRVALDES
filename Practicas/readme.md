# Nombre del proyecto

Parpadeo de LED con Arduino (Blink)

## Descripción

El objetivo de este código expone como prender y apagar un led.

## Objetivos de aprendizaje

Programar y simular en Arduino el encendido y apagado intermitente (parpadeo) de un LED conectado al pin digital 13, utilizando la función delay() para generar un efecto visualmente perceptible.

## Material utilizado

Enumera todos los componentes usados:

* Arduino Uno R4 WiFi
* Protoboard
* Led
* Cables Dupont
* Resistencia 220 ohms

## Diagrama del circuito

<img width="300" height="300" alt="Diagrama practica arduino" src="https://github.com/user-attachments/assets/63a2609f-737c-4d30-9006-ca4d7ce4a4b6" />



## Código

// Encender 10 LEDs - Arduino Uno R3
// Cada LED tiene su propia variable

int led1 = 2;
int led2 = 3;
int led3 = 4;
int led4 = 5;
int led5 = 6;
int led6 = 7;
int led7 = 8;
int led8 = 9;
int led9 = 10;
int led10 = 11;

void setup() {
  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
  pinMode(led4, OUTPUT);
  pinMode(led5, OUTPUT);
  pinMode(led6, OUTPUT);
  pinMode(led7, OUTPUT);
  pinMode(led8, OUTPUT);
  pinMode(led9, OUTPUT);
  pinMode(led10, OUTPUT);
}

void loop() {
  digitalWrite(led1, HIGH);
  digitalWrite(led2, HIGH);
  digitalWrite(led3, HIGH);
  digitalWrite(led4, HIGH);
  digitalWrite(led5, HIGH);
  digitalWrite(led6, HIGH);
  digitalWrite(led7, HIGH);
  digitalWrite(led8, HIGH);
  digitalWrite(led9, HIGH);
  digitalWrite(led10, HIGH);
}

## Video del funcionamiento

[Readme](ruta/a/tu/archivo)

[Ver video en YouTube](https://youtube.com/shorts/op4nnYcA8Ng?feature=share)

## Reporte

https://www.google.com/url?sa=E&source=gmail&q=https://drive.google.com/file/d/1hVAEnLIs9dwElO8hZ47nfIvId0YkBo6y/view?usp=drive_web 

* Gráficas (insertar imagen o link)
* Tablas de datos
* Observaciones sobre el comportamiento del sistema

## Conclusiones

La práctica permitió reforzar el uso de las funciones básicas de salida digital y temporización en Arduino (digitalWrite y delay), así como comprender el funcionamiento eléctrico de un protoboard, la importancia de que los componentes queden conectados en serie para que la resistencia cumpla su función de limitar la corriente. Este tipo de error es común en simuladores como Tinkercad y resalta la importancia de verificar el camino real de la corriente, no solo la presencia física de los componentes en el circuito.

## Resultados

[https://www.google.com/url?sa=E&source=gmail&q=https://drive.google.com/file/d/1hVAEnLIs9dwElO8hZ47nfIvId0YkBo6y/view?usp=drive_web)

Este documento contiene la descripción de la práctica, objetivos y procedimientos realizados.

* Reporte técnico estilo IEEE (PDF)
* Datos CSV (si aplica)
* Diagramas adicionales
