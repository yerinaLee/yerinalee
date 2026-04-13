<h1 align="center">Hi 👋, I'm Yerina Lee(이예리나)!</h1>
<h3 align="center">Backend Developer who builds stability through automation</h3>
<p align="center">
  <strong>60% less support requests</strong> | <strong>90% faster operations</strong> | <strong>Zero-Downtime mindset</strong>
</p>

---

## 💼 About Me

**Backend Developer (2Y)**

반복되는 문제 앞에서 임시방편보다 구조를 바꾸는 쪽을 택하는 개발자입니다.<br>
팝업 배포 구조를 무배포 방식으로 전환해 협업 비용을 60% 줄이고, 50여 대 서버의 로그 관리를 자동화해 수작업을 90% 걷어냈습니다.
레거시 환경에서 문제의 근본을 찾고, 팀 전체의 운영 체력을 키우는 일에 관심이 많습니다.

레거시가 쌓인 환경에서 시스템을 깊게 이해하고, 안정적으로 개선하는 역할을 선호합니다.

---

## 🏆 Key Achievements

### **Operational Efficiency**
- 🚀 **No-Deploy Popup System**: 무배포 방식 리팩토링으로 개발 일정 단축 (**3일 → 1일**) 및 커뮤니케이션 **60% 감소**
- ⚡ **CI/CD Optimization**: Jenkins 파이프라인 내 로그 자동 압축 쉘 연동으로 수동 작업 시간 **90% 단축**
- 🔧 **Automation Tool**: Python 기반 CS 키워드 모니터링 및 크롬 익스텐션 개발로 이슈 선제 대응

### **Stability & Monitoring**
- 🛡️ **Zero Capacity Incidents**: Fluentd 로그 모니터링 및 자동 삭제 스크립트(crontab) 도입 후 **용량 이슈 장애 0건**
- 📊 **Server Health Check**: SMTP 연동 서버 용량 알림 시스템 구축으로 10여 대 서버 상태 실시간 가시성 확보
- 🧪 **TDD Adoption**: 캐시 페이백 로직 등 민감한 금융 데이터 처리 시 테스트 자동화를 통한 로직 무결성 검증

### **Service Migration**
- 🌏 **Global-to-KR Migration**: 타사 서비스 이관 프로젝트의 핵심 기능(인증, 본인인증 미들서버, 이관코드 복원) 전담 개발

---

## 🛠 Tech Stack

### **Backend & Language**
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Groovy](https://img.shields.io/badge/Groovy-4298B8?style=flat&logo=apache-groovy&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

### **Database & Infrastructure**
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 📌 Featured Projects

### 🏗️ **No-Deploy Popup System (Redis & CDN)**
**"또 배포해야 해요?" 를 없애기 위한 구조 개선**

반복적으로 들어오는 팝업 이벤트 요청마다 배포가 필요한 구조가 비효율적이라고 판단, 무배포 방식으로 전면 리팩토링했습니다.
- Jsoup 기반 CDN 리소스 파싱 구조 설계로 배포 없는 실시간 업데이트 구현
- 디자인팀이 CDN 파일만 수정하면 개발팀 개입 없이 반영되는 구조로 개선
- 협업 비용 60% 절감, 개발 일정 3일 → 최대 1일로 단축

### 🔄 **KR Service Migration Platform**
**이종 플랫폼 간 데이터 이관 및 인증 시스템 구축**

타사에서 운영하던 서비스를 자체 플랫폼으로 이관하면서, 기존 인증 체계를 새로운 국내 결제사 연동으로 처음부터 설계했습니다.
- 본인인증 모듈 연동을 위한 미들서버 구축 및 이기종 통신 설계
- 배포 후 발견된 보안 취약점(Client-side 로직)을 즉시 Server-side로 이관 처리
- 재사용성을 고려한 코드 구조로 후속 기능 개발 공수 절감

### 🤖 **Server Monitoring & Automation Pipeline**
**새벽에 깨지 않기 위한 자동화**

50여 대 서버의 용량 이슈로 새벽 대응이 반복되던 문제를 자동화로 해결했습니다.
- Jenkins Pipeline + Bash를 이용한 전 서버 로그 자동 압축 파이프라인 구축
- Fluentd 로그 자동 모니터링 및 crontab 기반 자가 복구 스크립트 구축
- SMTP 기반 서버 용량 알림 시스템으로 이슈 선제 대응 체계 마련
- 도입 이후 용량 이슈로 인한 장애 **0건**
