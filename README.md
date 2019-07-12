# Ud2_Ejemplo10
_Ejemplo 10 de la Unidad 2._ 

Vemos un ejemplo de GridLayout con una tabla de 3x3.

Sólo hemos de fijarnos en el fichero _activity_main.xml_: 

```
<GridLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:columnCount="3"
    android:rowCount="3">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="1"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="2"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="3"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="4"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="5"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="6"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="7"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="8"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="9"/>
</GridLayout>
```

Los elementos se irán posicionando en orden, primero llenando la primera fila, después la segunda, etc.
