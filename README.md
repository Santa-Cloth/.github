# 🪄 Wizard of Ounce : 의류 추천 시스템
> 패션 MD의 매입 의사결정을 지원하는 데이터 기반 의류 추천 웹 서비스

## 📌 프로젝트 소개 
- 개발 기간: 2025.12.24 ~ 2026.03.05 (10주)
- 서비스 목적: 상품 스타일 분석과 트렌드 데이터를 함께 제공하여 매입 상품 선정에 필요한 정보를 지원
- 핵심 기능:
  - 이미지 스타일 분석 및 유사 상품 추천
  - 네이버 쇼핑 기반 스타일 트렌드 분석
  - 매입 후보 상품 저장 기능
  - 상품 및 매출 데이터 시각화 대시보드

## 🛠 기술 스택 
- Frontend: <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Next-black.svg?style=flat-square&logo=next.js&logoColor=white"> <img src="https://img.shields.io/badge/tailwindCSS-06B6D4.svg?style=flat-square&logo=tailwind-css&logoColor=white">
- Backend: <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciICB2aWV3Qm94PSIwIDAgNTAgNTAiIHdpZHRoPSI1MHB4IiBoZWlnaHQ9IjUwcHgiPjxwYXRoIGQ9Ik0gMjguMTg3NSAtMC4wMDM5MDYyNSBDIDMwLjkzNzUgNi4zNTkzNzUgMTguMzIwMzEzIDEwLjI4OTA2MyAxNy4xNTIzNDQgMTUuNTkzNzUgQyAxNi4wNzQyMTkgMjAuNDYwOTM4IDI0LjY0MDYyNSAyNi4xMjEwOTQgMjQuNjQ0NTMxIDI2LjEyMTA5NCBDIDIzLjM0Mzc1IDI0LjEwNTQ2OSAyMi40MDIzNDQgMjIuNDQxNDA2IDIxLjA5NzY1NiAxOS4zMDQ2ODggQyAxOC44OTA2MjUgMTQgMzQuNTMxMjUgOS4yMDMxMjUgMjguMTg3NSAtMC4wMDM5MDYyNSBaIE0gMzYuNTUwNzgxIDguODEyNSBDIDM2LjU1MDc4MSA4LjgxMjUgMjUuNTAzOTA2IDkuNTExNzE5IDI0Ljk0MTQwNiAxNi41ODIwMzEgQyAyNC42OTE0MDYgMTkuNzMwNDY5IDI3Ljg0Mzc1IDIxLjQxMDE1NiAyNy45Mzc1IDIzLjcwMzEyNSBDIDI4LjAwNzgxMyAyNS41NzAzMTMgMjYuMDUwNzgxIDI3LjEyODkwNiAyNi4wNTA3ODEgMjcuMTI4OTA2IEMgMjYuMDUwNzgxIDI3LjEyODkwNiAyOS42MDE1NjMgMjYuNDYwOTM4IDMwLjcxNDg0NCAyMy42MDU0NjkgQyAzMS45NDUzMTMgMjAuNDM3NSAyOC4zMjgxMjUgMTguMjczNDM4IDI4LjY5MTQwNiAxNS43MzgyODEgQyAyOS4wNDI5NjkgMTMuMzEyNSAzNi41NTA3ODEgOC44MTI1IDM2LjU1MDc4MSA4LjgxMjUgWiBNIDM5LjIzMDQ2OSAyNS4xNDQ1MzEgQyAzOC4wNzQyMTkgMjUuMDkzNzUgMzYuNzg5MDYzIDI1LjQ3NjU2MyAzNS42MjUgMjYuMzEyNSBDIDM3LjkwNjI1IDI1LjgyNDIxOSAzOS44MzU5MzggMjcuMjE4NzUgMzkuODM1OTM4IDI4LjgyODEyNSBDIDM5LjgzNTkzOCAzMi40NTMxMjUgMzQuNTk3NjU2IDM1Ljg3ODkwNiAzNC41OTc2NTYgMzUuODc4OTA2IEMgMzQuNTk3NjU2IDM1Ljg3ODkwNiA0Mi43MDcwMzEgMzQuOTUzMTI1IDQyLjcwNzAzMSAyOSBDIDQyLjcwNzAzMSAyNi41MzkwNjMgNDEuMTUyMzQ0IDI1LjIzNDM3NSAzOS4yMzA0NjkgMjUuMTQ0NTMxIFogTSAxOS4xODM1OTQgMjUuMTUyMzQ0IEMgMTkuMTgzNTk0IDI1LjE1MjM0NCA5LjA2MjUgMjUuMDE1NjI1IDkuMDYyNSAyNy44Nzg5MDYgQyA5LjA2MjUgMzAuODcxMDk0IDIyLjMxNjQwNiAzMS4wODIwMzEgMzEuNzgxMjUgMjkuMjM4MjgxIEMgMzEuNzgxMjUgMjkuMjM4MjgxIDM0LjMwODU5NCAyNy41MDc4MTMgMzQuOTgwNDY5IDI2Ljg2MzI4MSBDIDI4Ljc3NzM0NCAyOC4xMjg5MDYgMTQuNjIxMDk0IDI4LjI5Njg3NSAxNC42MjEwOTQgMjcuMjAzMTI1IEMgMTQuNjIxMDk0IDI2LjE5MTQwNiAxOS4xODM1OTQgMjUuMTUyMzQ0IDE5LjE4MzU5NCAyNS4xNTIzNDQgWiBNIDE2LjczODI4MSAzMC43MjI2NTYgQyAxNS4xODc1IDMwLjcyMjY1NiAxMi44NzEwOTQgMzEuOTIxODc1IDEyLjg3MTA5NCAzMy4wNzgxMjUgQyAxMi44NzEwOTQgMzUuNDAyMzQ0IDI0LjU2MjUgMzcuMTk1MzEzIDMzLjIxODc1IDMzLjc5Njg3NSBMIDMwLjIyMjY1NiAzMS45NjA5MzggQyAyNC4zNTU0NjkgMzMuODM5ODQ0IDEzLjUzOTA2MyAzMy4yMzgyODEgMTYuNzM4MjgxIDMwLjcyMjY1NiBaIE0gMTguMTc5Njg4IDM1LjkyMTg3NSBDIDE2LjA1MDc4MSAzNS45MjE4NzUgMTQuNjcxODc1IDM3LjIzNDM3NSAxNC42NzE4NzUgMzguMjAzMTI1IEMgMTQuNjcxODc1IDQxLjE4NzUgMjcuMzc4OTA2IDQxLjQ4ODI4MSAzMi40MTQwNjMgMzguNDUzMTI1IEwgMjkuMjE0ODQ0IDM2LjQxNzk2OSBDIDI1LjQ1MzEyNSAzOC4wMDc4MTMgMTYuMDA3ODEzIDM4LjIyMjY1NiAxOC4xNzk2ODggMzUuOTIxODc1IFogTSAxMS4wODk4NDQgMzguNjI1IEMgNy42MjEwOTQgMzguNTU0Njg4IDUuMzY3MTg4IDQwLjExMzI4MSA1LjM2NzE4OCA0MS40MDYyNSBDIDUuMzYzMjgxIDQ4LjI4MTI1IDQwLjg5MDYyNSA0Ny45NDkyMTkgNDAuODkwNjI1IDQwLjkyMTg3NSBDIDQwLjg5MDYyNSAzOS43NTc4MTMgMzkuNTE1NjI1IDM5LjIwMzEyNSAzOS4wMTk1MzEgMzguOTM3NSBDIDQxLjkyMTg3NSA0NS42NTYyNSA5Ljk2ODc1IDQ1LjEzNjcxOSA5Ljk2ODc1IDQxLjE3MTg3NSBDIDkuOTY4NzUgNDAuMjY5NTMxIDEyLjMxMjUgMzkuMzgyODEzIDE0LjQ5MjE4OCAzOS44MDg1OTQgTCAxMi42NDQ1MzEgMzguNzU3ODEzIEMgMTIuMTAxNTYzIDM4LjY3NTc4MSAxMS41ODIwMzEgMzguNjMyODEzIDExLjA4OTg0NCAzOC42MjUgWiBNIDQ0LjYzNjcxOSA0My4yNSBDIDM5LjIzNDM3NSA0OC4zNjcxODggMjUuNTQ2ODc1IDUwLjIzNDM3NSAxMS43ODEyNSA0Ny4wNzQyMTkgQyAyNS41NDI5NjkgNTIuNzAzMTI1IDQ0LjU2NjQwNiA0OS41MzUxNTYgNDQuNjM2NzE5IDQzLjI1IFoiLz48L3N2Zz4=&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=Spring-Security&logoColor=white"/> Spring Data JPA
- Database: <img src="https://img.shields.io/badge/Postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
- Data/AI: <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/FastAPI-009688.svg?style=flat-square&logo=fastapi&logoColor=white"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=flat-square&logo=pytorch&logoColor=white">
  
##  🧑‍💻 역할 분담
| **이동규(Frontend)** | **김현지(Backend)** | **윤치형(Backend)** | **김향자(Data/AI)** | **황성훈(Data/AI)** |
|:---:|:---:|:---:|:---:|:---:|
| <img src="https://github.com/eststar.png" width="400"> <br>[@eststar](https://github.com/eststar) | <img src="https://github.com/guswlrla.png" width="400"> <br>[@guswlrla](https://github.com/guswlrla) | <img src="https://github.com/nx2803.png" width="400"> <br>[@nx2803](https://github.com/nx2803) | <img src="https://github.com/khhjj5298.png" width="400"> <br>[@khhjj5298](https://github.com/khhjj5298) | <img src="https://github.com/carnelli95.png" width="400"> <br>[@carnelli95](https://github.com/carnelli95) |

## ⚙️ 프로젝트 아키텍처
<img width="1634" height="658" alt="아키텍처" src="https://github.com/user-attachments/assets/f2c6fcf8-48c9-4b19-8ff3-e1881d1f7b28" />

## 🗂️ ERD
<img width="800" height="800" alt="erd" src="https://github.com/user-attachments/assets/7725600b-1abd-4928-8c75-52b2373d9a02" />

## 🔍 주요 기능
  ### 1. 메인 화면
  > 이미지 기반 추천, 보유 상품 기반 추천, 관리자 대시보드 세 가지 기능으로 구성된 서비스
  <img width="80%" alt="메인화면" src="https://github.com/user-attachments/assets/b862a33b-828d-4726-a3cc-a614d036fc0d" />
  
  ### 2. 분석 대상 선택
  > 의류 이미지를 업로드하거나 나인온스 보유 상품을 선택해 스타일 분석 수행 
  <img width="49%" alt="업로드화면" src="https://github.com/user-attachments/assets/720fbd39-f850-4859-b4ba-bd9536b95060" />
  <img width="49%" alt="보유상품(9oz)목록" src="https://github.com/user-attachments/assets/b7e1904e-12c1-41ec-bbe5-839b3f3dd732" />

  ### 3. 스타일 분석 결과
  > GCN 또는 FashionCLIP 모델을 선택하여 스타일 분석 결과를 확인하고, 네이버 쇼핑 데이터를 활용한 패션 트렌드 정보 제공
  <img width="49%" alt="gcn_분석결과" src="https://github.com/user-attachments/assets/c91e81a4-f7c5-460f-9a4b-36f93cae83a3" />
  <img width="49%" alt="clip_분석결과" src="https://github.com/user-attachments/assets/fb07a155-1093-4a2c-862c-89d71e45e86e" />

  ### 4. 유사한 상품 추천
  > 분석된 이미지와 유사한 나인온스 상품 및 외부 상품을 추천
  <img width="49%" alt="분석결과_9oz목록" src="https://github.com/user-attachments/assets/ad9bbd3b-ac0b-49a8-ab05-fc27808d55e1" />
  <img width="49%" alt="분석결과_외부목록" src="https://github.com/user-attachments/assets/c8d149e0-92ca-4f95-b29f-2d0de7a8c004" />
  
  ### 5. 매입 후보 상품 저장
  > 관심 있는 외부 상품을 저장하고 매입 후보 상품을 관리
  <img width="80%" alt="북마크" src="https://github.com/user-attachments/assets/9001a1f6-fabf-4b65-97eb-5629bde0304e" />

  ### 6. 관리자 대시보드
  > 매장별 상품 판매량 순위와 스타일 차트를 제공하여 상품 운영 의사결정 지원
  <img width="80%" alt="대시보드" src="https://github.com/user-attachments/assets/8d9d993a-12f6-435a-9da0-b2148e221083" />

  ### 7. 스타일 클러스터
  > 나인온스 상품의 스타일 분포를 시각화해 스타일 편중 여부를 파악
  <img width="49%" alt="gcn_스타일맵" src="https://github.com/user-attachments/assets/303a6421-7d79-4658-b7d0-426c33020e31" />
  <img width="49%" alt="clip_스타일맵" src="https://github.com/user-attachments/assets/16c616ec-0303-40de-924c-116220ca4afc" />

## 📹 시연 영상
[▶ 시연 영상 보기](https://youtu.be/ZDTq16FxzdA?si=vhrTFIFuD6uZOXEf)
