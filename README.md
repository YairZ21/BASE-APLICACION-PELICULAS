# 🎬 Screenmatch: ¡Tu Buscador de Series Favorito! 🍿

¡Bienvenido a **Screenmatch**!  
¿Te imaginas tener un superpoder para buscar, guardar y explorar series y episodios como un verdadero cinéfilo?  
¡Pues este proyecto Java con Spring Boot lo hace posible! 🚀

---

## 🚦 ¿Qué puedes hacer aquí?

- 🔍 **Buscar series** por nombre y guardarlas en tu base de datos.
- 📺 **Consultar episodios** de tus series favoritas y almacenarlos.
- 🏆 **Ver el Top 5** de series y episodios mejor evaluados.
- 🎭 **Filtrar** por género, temporadas o evaluación.
- 🕵️‍♂️ **Buscar episodios** por nombre.
- ¡Y mucho más desde un menú interactivo en consola!

---

## 🛠️ Tecnologías que hacen la magia

- ☕ Java 17+
- 🌱 Spring Boot
- 🗃️ Spring Data JPA
- 🧪 H2 Database (¡puedes cambiarla si quieres!)
- 🧰 Maven
- 🎬 OMDb API

---

## 🚀 ¿Cómo lo pongo a funcionar?

1. **Clona este repo:**
   ```bash
   git clone https://github.com/tu-usuario/screenmatch.git
   cd screenmatch

1.Configura la base de datos en application.properties si deseas usar otra distinta a H2.
2.Ejecuta la aplicación:
mvn spring-boot:run
3.Sigue las instrucciones del menú en consola.


Uso
Al iniciar la aplicación, se mostrará un menú interactivo en consola donde podrás:


Buscar y guardar series y episodios.
Listar y filtrar series.
Consultar episodios por nombre o por serie.
Ver los mejores episodios y series según la evaluación.

🗂️ Estructura del proyecto
model/: Entidades JPA y enums.
repository/: Interfaces de acceso a datos.
service/: Servicios para consumo de API y conversión de datos.
Principal/: Lógica principal y menú de la aplicación.


Créditos
Desarrollado por YairZ21.


Licencia
Este proyecto está bajo la licencia MIT.
