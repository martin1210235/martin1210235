<div align="center">

# Martín Herranz-Sánchez

**Telecommunications engineer. I build real-time video systems and applied AI tooling.**

MSc in Telecommunication Engineering at ETSIT, Universidad Politécnica de Madrid
· Exchange year at Czech Technical University in Prague

[![DOI](https://img.shields.io/badge/DOI-10.3390%2Fapp16189253-B31B1B)](https://doi.org/10.3390/app16189253)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--7781--7118-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0002-7781-7118)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-profile-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=4RysIO0AAAAJ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-profile-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/martin-herranz/)

</div>

---

## Published research

> **Beyond Hardware Mixers: A Resilient Cloud-Native Architecture for Real-Time Remote Video Production**
> Herranz Sánchez, M.; Llorente, Á.; del Rio, A.; Jiménez, D.
> *Applied Sciences* **16**(18), 9253 (2026). Open access.
> [doi:10.3390/app16189253](https://doi.org/10.3390/app16189253)

A live video mixer built as containerized microservices instead of dedicated hardware. The
measured result: no throughput penalty against a single-node deployment, and **1.8 s automatic
recovery from a node failure with zero dropped frames** in the programme output.

I am the first author, and the sole contributor for software, formal analysis, investigation
and the original manuscript, as recorded in the paper's CRediT statement. I built the system,
designed and ran the experiments, analysed the data and wrote the article.

---

## Selected work

### [voctomix-2.0](https://github.com/martin1210235/voctomix-2.0) · the system behind the paper

A Full-HD live video mixer that a production team can run on ordinary machines. Four camera
sources, compositing modes, audio that follows video, and a three-state stream blanker, all
wired over a line-based TCP control protocol. Packaged with Docker Compose and Kubernetes so a
full studio comes up reproducibly, with AMQP telemetry for monitoring and failover.

`Python` `GStreamer` `GTK` `Docker` `Kubernetes` `RabbitMQ`

---

## Also building

Private for now, because they run on my own data:

- **receipt-nutrition-tracker** — photograph a supermarket receipt and the app works out what
  is in your kitchen and what you have left to eat today. OCR extracts the line items, fuzzy
  matching resolves them against Open Food Facts, and a mobile web app tracks consumption
  against daily calorie and macro targets. `Python` `FastAPI` `Tesseract` `SQLite`
- **personal-automation-hub** — assembles a daily research digest from a curated source list
- **health-data-pipeline** — consolidates wearable exports into a queryable daily log

---

## Elsewhere

[ORCID](https://orcid.org/0009-0002-7781-7118) ·
[Google Scholar](https://scholar.google.com/citations?user=4RysIO0AAAAJ) ·
[LinkedIn](https://www.linkedin.com/in/martin-herranz/) ·
[Kaggle dataset](https://doi.org/10.34740/KAGGLE/DSV/19389804)
