# TempSense
indice:
+ Objetivo de la aplicacion
+ Proyectos de la aplicacion
+ Flujo de trabajo
+ Observaciones generales

## Objetivo
El objetivo principal de esta aplicacion, es monitorear la temperatura de las neveras en laboratorios que requieren un monioreo constante de sus productos y sustancias; ya que, deben cumplir unas normas establecidas para asegurar su calidad

## Proyectos de la apliacion
+ los de universal Windowpara Windows 10 que se instalaban en los dispositivos finales, pero van a cambiar, estos 3 proyectos ya son obsoletos
+ Windows service es un monitor que se est� ejecutando en un servidor; permanentemente, �l est� interactuando con azure para extraer los datos que est�n en la nube y ponerlos en la DB , es el que est� permanentemente trabajando y no se puede caer
+ El modelo, el modelo en bases de datos como tal, est� en este modelo.

Este programa se compone principalmente de 4 proyectos que seran descritos mas a fondo en sus respectivos README. md :
+  Active.TempSense. MailNotificaciones
+  Active.TempSense. Model
+  Active.TempSense. Web
+  Active.TempSense. WindowsService

## flujo de trabajo
![alt text][Flujo de trabajo]

[Flujo de trabajo]: (/Flujo de trabajo.jpg) "Flujo de trabajo"

## Observaciones generales