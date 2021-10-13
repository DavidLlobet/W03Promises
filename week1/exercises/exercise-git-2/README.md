1. Inicializa un repositorio local
2. Añade al stage todos los archivos y crea un commit inicial con todos ellos.
3. Abre el archivo lampara/lampara.java y añade esta nueva propiedad a la clase. Guarda el archivo.

```java
    private boolean tieneBombilla;
```

4. Abre el archivo lavadora/lavadora.java y haz que el método lava() sea privado. Guarda el archivo.
5. Añade los cambios al stage y haz un commit con ellos.
6. Abre el archivo lavadora/lavadora.java y corrige la visibilidad del método lava(), hazlo público. Guarda el archivo.
7. Abre el archivo lampara/lampara.java y añade este nuevo método. Guarda el archivo.

```java
    public void switch() {
        estaEncendida = !estaEncendida;
    }
```

8. Anota el hash del último commit que has hecho.
9. Añade únicamente la corrección del punto 6 al último commit que has hecho (sin crear un commit nuevo). ¿Su hash ha cambiado? ¿Por qué?
10. Crea un nuevo commit con el cambio del punto 7.
11. Comprueba que te ha quedado un log con tres commits.
12. Comprueba que en el penúltimo commit has corregido bien la visibilidad del método lava().
