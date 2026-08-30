<!--
GitHub Profile README.md

사용 방법
1. GitHub에서 본인 사용자명과 동일한 이름의 public repository를 만듭니다.
   예: GitHub 사용자명이 octocat이면 repository 이름도 octocat
2. 이 파일을 repository 루트에 README.md로 업로드합니다.
3. 아래 연락처, 블로그, GitHub 통계 카드의 YOUR_GITHUB_USERNAME 부분은 필요할 때 수정하세요.

Badge source: Simple Icons / Shields.io
- Python: python / 3776AB
- Java: openjdk / 437291
  * Simple Icons의 Java Coffee Cup 아이콘은 현재 제공되지 않아 OpenJDK 아이콘을 사용합니다.
- Apache Kafka: apachekafka / 231F20
- Apache Flink: apacheflink / E6526F
- Apache Hadoop: apachehadoop / 66CCFF
- Apache Hive: apachehive / FDEE21
- Apache Airflow: apacheairflow / 017CEE
- Apache Spark: apachespark / E25A1C
- Trino: trino / DD00A1
- PostgreSQL: postgresql / 4169E1
- MySQL: mysql / 4479A1
- Docker: docker / 2496ED
- Kubernetes: kubernetes / 326CE5
- AWS: amazonwebservices / FF9900
- Claude: claude / D97757
- Codex: 000000
  * Codex 배지에는 OpenAI 아이콘을 사용합니다.

Recommended additions for later
- Redis: redis / FF4438
- Git: git / F05032
- GitHub Actions: githubactions / 2088FF
- Terraform: terraform / 844FBA
- FastAPI: fastapi / 009688
- Spring Boot: springboot / 6DB33F
-->

<div align="center">

# 최지욱

### Data Engineer

</div>

---

## 🧑‍💻 About Me

데이터의 수집·처리·저장 과정을 직접 구현하며 데이터 엔지니어링 역량을 쌓고 있습니다. Kafka·Flink를 활용한 실시간 스트리밍, Airflow 기반 워크플로우, Spark 기반 분산 처리에 관심이 있습니다. 모빌리티 데이터를 다룬 경험도 있지만, 특정 도메인보다는 안정적으로 운영할 수 있는 데이터 파이프라인을 설계하고 개선하는 데 관심이 있습니다.

---

## 🛠️ Tech Stack

### Data Engineering

<p>
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Apache%20Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white" alt="Apache Flink" />
  <img src="https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black" alt="Apache Hadoop" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark" />
</p>

### Language

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-437291?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java / OpenJDK" />
</p>

### Query & Storage

<p>
  <img src="https://img.shields.io/badge/Trino%20%28Studying%29-DD00A1?style=for-the-badge&logo=trino&logoColor=white" alt="Trino (Studying)" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

### Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes%20%28Studying%29-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes (Studying)" />
</p>

### AI

<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Codex-000000?style=for-the-badge&logo=openai&logoColor=white" alt="Codex" />
</p>

---

## 📂 Projects

### Featured · Data Engineering

#### 🚗 드림학기 · 차량 주행 데이터 ETL 파이프라인

- 실시간 주행 센서 데이터와 정적 데이터를 각 특성에 맞게 분리 저장
- Trino로 이종 데이터베이스를 연결해 단일 쿼리 환경 구성
- 데이터 수집부터 저장·분석·시각화까지 이어지는 ETL 파이프라인 구축

`ETL` `Data Pipeline` `Trino` `Sensor Data`

#### 🔬 RUS · 실시간 이벤트 패턴 감지 플랫폼

- Flink CEP로 급정거·추월 등 주행 이벤트를 실시간 감지
- 이벤트 패턴으로 엣지 케이스를 선별하고 전후 센서·이미지 데이터를 연계 저장
- E2E 파인튜닝용 데이터 처리 플랫폼 구축 · 🏆 한국ITS학회 우수논문상

`Apache Flink` `Flink CEP` `Realtime Processing` `Edge Case Mining`

#### 🚕 Softeer 8th · NEXTMOVE

- 택시 운행·차량·에너지 데이터를 수집해 월 2천만 건 규모의 데이터 파이프라인 구축
- 원본(Bronze)–정제(Silver)–추천(Gold) 단계로 데이터를 나누는 메달리온 구조를 설계하고 EMR Serverless(Spark)·Airflow로 운영
- 데이터 품질·계보·모니터링을 관리하고 운행 데이터 기반 차량 교체 추천 대시보드 구축

`EMR Serverless` `Apache Spark` `Apache Airflow` `S3` `RDS`

### Other Experience · Autonomous Driving / Mobility

#### 🏎️ 2024 HL FMA 자율주행 경진대회

MORAI 환경에서 자율주행 제어를 설계하고 Vision·Planning 개발을 지원한 프로젝트 · 🏆 4등 특별상

`MORAI` `Autonomous Driving` `Control`

#### 🤝 2025 시각장애인 보조 모빌리티 ‘동행’

STT·TTS와 의도 인식을 활용해 음성 기반 HMI를 구축한 보행 모빌리티

`HMI` `STT` `TTS` `Intent Recognition`

#### 🧠 2026 CARLA Lane Following 강화학습

Lane Following을 MDP로 정의하고 강화학습 알고리즘별 성능을 비교하는 시뮬레이션

`CARLA` `Reinforcement Learning` `Lane Following`

---

## 🧩 Algorithm

[![Solved.ac Profile](https://mazassumnida.wtf/api/generate_badge?boj=jiwooki77)](https://solved.ac/jiwooki77)

---

<!--
## 📊 GitHub Stats

아래 YOUR_GITHUB_USERNAME을 본인 GitHub 사용자명으로 바꾼 뒤 주석을 해제하면 통계 카드가 표시됩니다.

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=transparent)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=transparent)

</div>
-->

<!--
## 📫 Contact

- Email: your-email@example.com
- Blog: https://your-blog-url
-->
