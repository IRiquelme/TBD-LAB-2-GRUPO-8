# Frontend

1. Instalar dependecias del proyecto
```
npm install
```

2. Compilar y correr proyecto
```
npm run serve
```

## Importante

Al ejecutar el proyecto, se mostrarán dos direcciones similares a las siguientes:

  - Local: [http://localhost:8080/]()
  - Network: [http://192.168.0.10:8080/]()

Es crucial abrir la ***dirección local***, ya que el frontend utiliza la ubicación del navegador para actualizar la posición del usuario. Al utilizar la dirección "Network", el navegador detecta la conexión como insegura y no permite la obtención de la ubicación, ya que se considera información sensible. Este problema no se presenta al usar la dirección "Local".