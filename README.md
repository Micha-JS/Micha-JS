# Hi, I'm Micha 👋

**Analytics Engineer · Berlin** — I build the pipelines and models that turn messy real-world signals into decisions.

Business Computer Scientist by training, engineer by practice. Four years of writing code professionally, plus a steady stream of side projects that keep me honest: if a design decision is bad, the sensor on my windowsill or the battery in the basement will tell me within a week.

My work sits where data engineering, analytics and physical systems overlap — energy markets, home telemetry, and anything where a measurement eventually has to justify itself against reality.

---

## 🔭 Featured projects

### ⚡ [energy-platform](https://github.com/Micha-JS/energy-platform)
An end-to-end data platform for the German electricity market.

Ingests public market data (SMARD, ENTSO-E) and PV/battery telemetry into a modelled warehouse, then puts it to work: a **battery dispatch optimizer**, **tariff counterfactuals** ("what would this household have paid on a dynamic tariff?"), and a **forecasting layer** for generation and load.

Built the way I'd build it at work — typed, tested, CI green from the first commit, one milestone per pull request. Ships with synthetic sample data, so you can clone it and have the full stack running without any credentials.

`Python` · `SQL` · `dbt-style modelling` · `Docker` · `optimization` · `time-series forecasting`

### 🌱 [planter-telemetry](https://github.com/Micha-JS/planter-telemetry)
A complete IoT telemetry pipeline, from microcontroller to dashboard.

ESP32 sensor pods publish over MQTT into an async ingestion service that validates every payload against a schema before it touches storage. Data lands in a time-series database and surfaces through provisioned dashboards. Ingestion is idempotent, so replays and duplicate deliveries are a non-event.

The whole thing comes up with a single `docker compose up` — a built-in simulator generates realistic sensor traffic, so real hardware is optional. The analytics layer forecasts when a reservoir runs dry and warns before it happens, rather than after.

`ESP32` · `MQTT / Mosquitto` · `asyncio` · `Pydantic` · `TimescaleDB` · `Grafana` · `Docker Compose`

---

## 🛠️ What I work with

| | |
|---|---|
| **Languages** | Python, SQL, a bit of R |
| **Data & analytics** | pandas, NumPy, Plotly, dimensional modelling, warehouse design |
| **Pipelines** | ETL/ELT design, idempotent ingestion, orchestration, systemd timers |
| **Storage** | PostgreSQL, TimescaleDB, SQLite, DuckDB |
| **Engineering** | Docker, Git, CI/CD, pytest, type hints, code review |
| **ML** | scikit-learn, time-series forecasting, feature engineering |
| **Hardware & IoT** | ESP32, MQTT, ESPHome, CadQuery, FDM printing |

---

## 🌍 Beyond the terminal

I care about the environment — plants, the sea, and the unglamorous engineering that actually decarbonises things. Most of my side projects end up somewhere near that theme, whether it's shifting a battery's charge window into the cheap, green hours or keeping a plant alive with less water.

I also design parametric CAD models and cast concrete bowls from 3D-printed molds.

⚡ **Fun fact:** I model data, but also clay.

👯 Happy to collaborate on projects around energy, sustainability, or sensors that measure something real.

---

📫 [LinkedIn](https://www.linkedin.com/in/michajs/)
