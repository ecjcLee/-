# Push-pull Cascode vs Telescopic Cascode

문제:
일반적인 Telescopic Cascode 증폭기와 비교하여 Push-pull Cascode 증폭기가 가지는 구조적 특징과 장단점을 설명해 보세요.

답:
두 회로의 가장 큰 차이점은 입력 신호의 인가 방식과 그에 따른 이득(Gain) 및 출력 범위(Swing)의 트레이드오프입니다.

1. Push-pull Cascode의 장점
- Telescopic 구조는 한쪽 소자만 증폭에 기여하는 반면, Push-pull은 상단 PMOS와 하단 NMOS가 모두 입력에 반응하여 증폭에 기여합니다. 따라서 전체 트랜스컨덕턴스가 g_{m,n} + g_{m,p}가 되어 더 높은 이득을 얻을 수 있습니다.
- 출력단에서 Push(밀어내기)와 Pull(당기기) 동작이 모두 일어나 부하 커패시턴스를 더 빠르게 충·방전할 수 있으므로 고속 동작에 유리합니다.

2. Push-pull Cascode의 단점
- 각 소자가 포화 영역을 유지하기 위한 V_DS,sat이 필요하므로 출력 스윙이 좁아집니다.
