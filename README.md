# 🧼 오늘의 세탁, 맑음 : 세탁 방법 검색 애플리케이션

**"오늘의 날씨, 오늘의 옷차림, 오늘의 세탁 추천까지!"**  
이 프로그램은 실시간 날씨를 기반으로 빨래 지수와 추천 옷차림, 머신러닝을 활용한 세탁 지식 등을 제공하는  
Windows용 데스크탑 애플리케이션입니다.

### ✅ 설치 파일 다운로드

👉 [설치 파일](https://drive.google.com/file/d/1buAxfrwRYs28pZ3KdoZM3ubuyYN9SR4s/view?usp=sharing)에서 `Setup.exe` 다운로드

---

## ✨ 주요 기능

### 🌤 홈 화면 – 날씨 및 세탁 지수
- 현재 지역 날씨 정보 (온도, 습도, 구름량)
- 사용자 선호도에 따른 빨래 지수 계산
- 추천 옷차림 / 비추천 옷차림 제공

![스크린샷 2025-04-02 135718](https://github.com/user-attachments/assets/1052363d-56a3-4f6e-8159-aa5f63fc7cd7)

---

### 👕 Kind – 옷 검색 세탁법
- 옷 종류를 정확하게 모르는 경우엔 업로드 한 사진을 바탕으로 구별하여 세탁법 제공 가능
- 니트, 청바지, 코트 등 다양한 옷 구별 가능

![스크린샷 2025-04-02 135613](https://github.com/user-attachments/assets/ae9012cd-f2a5-4715-bf11-90dcaf51d57a)

---

### 💬 Q&A – 세탁 고민 상담
- 얼룩 제거 방법
- 냄새 제거 팁
- 자주 묻는 세탁 질문에 대한 추천 답변

![스크린샷 2025-04-02 135654](https://github.com/user-attachments/assets/9a1a80ca-8748-49c8-8965-3461919df75b)

---

### 🔖 Label – 세탁 기호 해설
- 옷에 붙은 세탁 기호 이미지 해설
- 건조/다림질/표백제 사용법 안내

![스크린샷 2025-04-02 135645](https://github.com/user-attachments/assets/50d08a59-cd5c-4847-a96c-c2cd723b88cd)

---

### 👕 Kind – 옷 종류별 세탁법
- 니트, 청바지, 코트 등 다양한 옷별 세탁법 제공
- 적절한 세제, 온도, 건조 방법 안내

![스크린샷 2025-04-02 135627](https://github.com/user-attachments/assets/e7db4d46-7429-4d69-a369-784e3a0548eb)

---

## 🖥 설치 방법

### ✅ 1. 설치 파일 다운로드

👉 [설치 파일](https://drive.google.com/file/d/1buAxfrwRYs28pZ3KdoZM3ubuyYN9SR4s/view?usp=sharing)에서 `Setup.exe` 다운로드

### ✅ 2. 실행 및 설치

- `Setup.exe` 실행
- 설치 후 자동 실행되며, 바탕화면 아이콘 또는 시작 메뉴에서 재실행 가능

---

## 🧩 기술 스택

- WPF (.NET Core 3.1 / .NET 5.0)
- ML.NET (옷 이미지 분류 모델 적용)
- OpenWeatherMap API (날씨 정보)
- 이미지 및 리소스 포함 배포 (Inno Setup 기반 설치기)

---

## 📦 배포 구조

- `Setup.exe` : 설치 마법사 실행 파일
- 설치 위치: `C:\Program Files (x86)\WashingApp\` (수정 가능)
- 내부 파일: `Launcher.exe`, `TodayWashing.exe`, `Fashion_ConsoleApp1.exe`, 모델 파일 등

---

## 🛠 개발자

- 👤 오정환 | JeonBuk National University, Korea
- ✉️ softhaim@gmail.com

---

## 📸 추가 스크린샷

> (필요하다면 더 많은 이미지 첨부 가능)

---
