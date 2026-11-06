# OxWind · 황소바람 실험 장치

한지 창의 구멍 크기에 따른 열 손실과 CO2 환기를 측정하는 고등학교 R&E 실험 장치(황소바람)의 웹 문서 및 3D 모델, 제어보드 배선도 저장소입니다.

## 📄 주요 페이지 및 문서

1. **메인 설계 문서 (index.html)**
   - 한지창 실험 장치 설계 보고서 및 측정 원리
   - [3D 장치 모델 뷰어 (pparatus.html)](apparatus.html) 내장
   - [아크릴 가공 부품 목록 및 의뢰서 (crylic-order.pdf)](acrylic-order.pdf)
   - [구매 목록 엑셀 (parts.xlsx)](parts.xlsx)

2. **Nano 제어보드 배선도 (wiring.html)**
   - Arduino Nano R4 기반 Nano_Heater_CO2_Controller 배선 안내도
   - 메뉴 버튼으로 센서/커넥터별 실물 모양, 플러그, 핀맵 확인 및 작업 체크리스트 제공

| 커넥터 | 연결 장치 |
|---|---|
| J10 | ATX 파워 (12V) |
| U6, U7 | CO2 센서 CM1107N A, B |
| U2, U4, U5, U10 | DS18B20 T1, T2, T3, PLATE |
| J11 / H3 / H4 | 히터판 / 히터 MOSFET / INA219 |
| J13(J12) / H5 | 솔레노이드 밸브 / 밸브 MOSFET |

---
Designed by CSHS (창원과학고).