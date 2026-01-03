<div align="center">
  
  # Hola, soy Francisco Luis Carrillo 👋
  
  ### Data Engineering Student | Finance & Product Specialist
  
  *Uniendo la lógica de negocios del Mercado de Capitales con la potencia de la Ingeniería de Datos.*

  [Linkedin](https://www.linkedin.com/in/franciscoluiscarrillo/) &nbsp; | &nbsp; [Portfolio](https://franciscoluiscarrillo.github.io/MiPortafolio/) &nbsp; | &nbsp; [Email](mailto:carrillo.francisco.luis@gmail.com)

</div>

---

### 🚀 Sobre mí

Soy un profesional con un sólido background en **Mercado de Capitales, Finanzas y Contabilidad**. Durante mi trayectoria, descubrí que mi verdadera pasión no estaba solo en analizar los números, sino en construir la infraestructura que los mueve.

Decidí dar un giro a mi carrera adentrándome en la programación y los datos. Hoy, mi objetivo es **combinar mi conocimiento de negocio** con mis nuevas habilidades técnicas para agregar valor como **Data Engineer**, diseñando flujos de datos que no solo funcionen técnicamente, sino que resuelvan problemas reales de negocio.

---

### 🛠️ Tech Stack & Herramientas

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
</div>

---

### 🎓 Educación

<table width="100%">
  <tr>
    <td width="120" align="center">
      <a href="https://www.frgp.utn.edu.ar/carreras/tup_tuss">
        <img src="https://www.frgp.utn.edu.ar/public/frontend/assets/img/logo-footer.png" width="100px" alt="UTN FRGP Logo">
      </a>
    </td>
    <td>
      <strong><a href="https://www.frgp.utn.edu.ar/carreras/tup_tuss">Tecnicatura Universitaria en Programación</a></strong><br>
      <em>UTN General Pacheco</em><br>
      <font size="2">En curso | Buenos Aires, Argentina</font>
    </td>
  </tr>
  <tr>
    <td width="120" align="center">
      <a href="https://www.unlu.edu.ar/">
        <img src="https://www.unlu.edu.ar/imagenes/logo.png" width="80px" alt="UNLu Logo">
      </a>
    </td>
    <td>
      <strong><a href="https://www.unlu.edu.ar/carg-contador-pre.html">Contador Público</a></strong><br>
      <em>Universidad Nacional de Luján</em><br>
      <font size="2">Título de Grado (Suspendido)</font>
    </td>
  </tr>
</table>

---

### 🏗️ Arquitectura de Datos (Enfoque)

```mermaid
graph LR
    A[Fuentes de Datos] -->|Ingesta| B[(Bronze Layer)]
    style B fill:#cd7f32,stroke:#333,stroke-width:2px,color:black
    
    B -->|Limpieza & Validación| C[(Silver Layer)]
    style C fill:#c0c0c0,stroke:#333,stroke-width:2px,color:black
    
    C -->|Agregación de Negocio| D[(Gold Layer)]
    style D fill:#ffd700,stroke:#333,stroke-width:2px,color:black
    
    D --> E[Analytics / BI / ML]
    
    subgraph Data Lakehouse
    B
    C
    D
    end
