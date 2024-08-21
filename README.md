# MemoTest Game

## Descripción

MemoTest Game es una aplicación de memoria construida con React. El objetivo del juego es encontrar pares de emojis coincidentes. Los bloques de memoria se voltean para revelar el emoji y los jugadores deben recordar las posiciones para hacer coincidir los pares. El juego incluye animaciones y lógica para manejar las selecciones y comparaciones de bloques.

## Tecnologías Utilizadas

- **React**: Biblioteca de JavaScript para construir interfaces de usuario.
- **CSS**: Para los estilos de los componentes.

## Estructura del Proyecto

- **`src/`**: Contiene los archivos fuente del proyecto.
  - **`App.js`**: Componente principal de la aplicación que maneja el estado del juego y la lógica.
  - **`components/`**: Directorio con los componentes de la aplicación.
    - **`Board/Board.js`**: Componente que representa el tablero del juego y renderiza los bloques de memoria.
    - **`MemoBlock/MemoBlock.js`**: Componente que representa un bloque de memoria individual.
  - **`App.css`**: Estilos globales para el componente `App`.
  - **`components/Board/Board.css`**: Estilos específicos para el componente `Board`.
  - **`components/MemoBlock/MemoBlock.css`**: Estilos específicos para el componente `MemoBlock`.

## Instalación

Para ejecutar la aplicación localmente, sigue estos pasos:

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/SoteloJoaquin/MemoTest.git
   git clone git@github.com:SoteloJoaquin/MemoTest.git
   ```

2. **Navega al directorio del proyecto**:

   ```bash
   cd MemoTest
   ```

3. **Instala las dependencias**:

   ```bash
   npm install
   ```

4. **Inicia la aplicación**:

   ```bash
   npm start
   ```

   La aplicación se abrirá en tu navegador por defecto en `http://localhost:3000`.

## Uso

- En el tablero del juego, cada bloque de memoria muestra una cara frontal vacía y una cara trasera con un emoji.
- Haz clic en un bloque para voltear y revelar el emoji.
- Intenta encontrar pares de bloques con el mismo emoji.
- Los bloques que no coinciden se volverán a ocultar después de un breve período.

## Contribución

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. **Fork del repositorio**.
2. **Crea una rama para tu característica**:

   ```bash
   git checkout -b mi-nueva-caracteristica
   ```

3. **Haz tus cambios y confirma**:

   ```bash
   git add .
   git commit -m "Añadir nueva característica"
   ```

4. **Empuja a tu repositorio**:

   ```bash
   git push origin mi-nueva-caracteristica
   ```

5. **Crea un Pull Request** en GitHub.

¡Gracias por tu interés en el MemoTest Game! Disfruta jugando y contribuyendo.
```
