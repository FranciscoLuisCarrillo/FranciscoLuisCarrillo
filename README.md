<div align="center">
  
  # Hola, soy Francisco Luis Carrillo 👋
  
  ### Data Engineer | Ex-Finance Specialist
  
  *Uniendo la lógica de negocios del Mercado de Capitales con la potencia de la Ingeniería de Datos.*

  [Linkedin](https://www.linkedin.com/in/franciscoluiscarrillo/) &nbsp; | &nbsp; [Portfolio](https://franciscoluiscarrillo.github.io/MiPortafolio/) &nbsp; | &nbsp; [Email](mailto:carrillo.francisco.luis@gmail.com)

</div>

---

### 🚀 Sobre mí

Soy un profesional con un sólido background en **Mercado de Capitales, Finanzas y Contabilidad**. Durante mi trayectoria, descubrí que mi verdadera pasión no estaba solo en analizar los números, sino en construir la infraestructura que los mueve.

Decidí dar un giro a mi carrera adentrándome en la programación y los datos. Hoy, mi objetivo es **combinar mi conocimiento de negocio** con mis nuevas habilidades técnicas para agregar valor como **Data Engineer**, diseñando flujos de datos que no solo funcionen técnicamente, sino que resuelvan problemas reales de negocio.

- 🔭 Actualmente trabajando en: **Proyectos de ETL y Automatización.**
- 🌱 Aprendiendo: **Arquitecturas de Big Data y Cloud Computing.**
- 🎯 Objetivo: **Construir pipelines de datos robustos y escalables.**

---

### 🛠️ Tech Stack

**Lenguajes & Core:**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>

**Data Engineering:**
<p>
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

### 📊 GitHub Analytics

<div align="center">
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=FranciscoLuisCarrillo&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Estadísticas de Francisco" height="180" />
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FranciscoLuisCarrillo&layout=compact&theme=radical&hide_border=true&langs_count=6" alt="Lenguajes más usados" height="180" />
  </a>
</div>

---

### 🏗️ Arquitectura de Datos (Enfoque)

Diseño pipelines siguiendo la arquitectura Medallón para garantizar calidad y trazabilidad.

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
