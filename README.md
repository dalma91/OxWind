# OxWind · 황소바람 실험 장치

한지 창의 구멍 크기에 따른 열 손실과 CO2 환기를 측정하는 실험 장치(황소바람)의 자료 저장소입니다.

## Nano 제어보드 배선도
- 파일: `index.html`
- GitHub Pages를 켜면 `https://dalma91.github.io/OxWind/` 에서 바로 볼 수 있습니다.
- 메뉴 버튼으로 센서·커넥터를 하나씩 골라 기판 커넥터 모양, 플러그, 전선 색, 장치 쪽 핀을 확인합니다.
- 핀 정보 출처: EasyEDA Pro 프로젝트 `Nano_Heater_CO2_Controller` (2026-11-06)

| 커넥터 | 연결 장치 |
|---|---|
| J10 | ATX 파워 (12V) |
| U6, U7 | CO2 센서 CM1107N A, B |
| U2, U4, U5, U10 | DS18B20 T1, T2, T3, PLATE |
| J11 / H3 / H4 | 히터판 / 히터 MOSFET / INA219 |
| J13(J12) / H5 | 솔레노이드 밸브 / 밸브 MOSFET |

Designed by CSHS (창원과학고).
