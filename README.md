```javascript
const agustin = {
    ubicacion: "Cordoba, Argentina",
    rol: "Software Developer",
    lenguajes: ["JavaScript", "TypeScript"],
    aprendiendo: ["Node.js", "React"],
    herramientas: ["Git", "GitHub"],

    saludar() {
        console.log(`Hola, soy ${this.rol} desde ${this.ubicacion}. Gracias por visitar mi perfil `);
    }
};

agustin.saludar();
```
