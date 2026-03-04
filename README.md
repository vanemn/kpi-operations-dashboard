# 📊 KPI Operations Dashboard

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

> Dashboard ejecutivo de KPIs operativos y financieros para monitorización de proyectos en tiempo real. Detecta desviaciones presupuestarias, analiza burn rate y visualiza el rendimiento de equipos.

---

## 📸 Vista del Dashboard

![Dashboard KPI](outputs/dashboard_kpi.png)

---

## 🎯 ¿Qué hace este proyecto?

Construye un sistema de monitorización de proyectos con 4 capas de análisis:

- **KPI Cards ejecutivas** — ingresos YTD, desviación, margen y proyectos activos de un vistazo
- **Evolución financiera** — presupuesto vs ejecutado mes a mes con detección de desviaciones
- **Margen operativo mensual** — alertas automáticas cuando no se alcanza el objetivo
- **Análisis por proyecto** — avance real vs planificado + Burn Rate vs progreso (con satisfacción del cliente)

---

## 💡 Indicadores Monitorizados

| KPI | Fórmula | Alerta |
|-----|---------|--------|
| Desviación presupuestaria | (Ejecutado - Presupuesto) / Presupuesto | > 2% |
| Margen operativo | (Ingresos - Costos) / Ingresos | < 8.5% |
| SPI (Schedule Performance Index) | Avance real / Avance planificado | < 0.95 |
| Burn Rate | Gasto actual / Presupuesto total | > % avance |
| Satisfacción cliente | Escala 1-5 | < 4.0 |

---

## 🗂️ Estructura

```
kpi-operations-dashboard/
│
├── 📓 kpi_dashboard.ipynb      # Notebook principal
├── 📁 outputs/
│   └── dashboard_kpi.png       # Dashboard exportado
├── requirements.txt
└── README.md
```

---

## ⚙️ Instalación

```bash
git clone https://github.com/vanemn/kpi-operations-dashboard.git
cd kpi-operations-dashboard
pip install -r requirements.txt
jupyter notebook kpi_dashboard.ipynb
```

---

## 👩‍💻 Autora

**Vanessa Morales Norambuena** — Project Manager | Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanessamoralesnorambuena)
[![GitHub](https://img.shields.io/badge/GitHub-vanemn-100000?style=flat&logo=github&logoColor=white)](https://github.com/vanemn)

