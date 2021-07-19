# Unmanned Aerial Vehicle-Aided Communications : Joint transmit Power and Trajectory Optimization
무인 항공기 통신의 전송파워와 이동 경로 최적화

## 상황
- UAV와 데이터를 주고 받는 노드들이 임의로 뿌려져 있는 상태
- UAV가 이동하면서 데이터를 받음
- 순서 : 임의의 노드가 hub 노드에게 데이터 전송 -> UAV 출발 지점에서 출발 -> hub를 돌면서 데이터를 받음 -> UAV 도착 지점에 도착

## 제한
- 전송 전력 제한
- 데이터 이동 속도 제한
- UAV 출발 지점 & 도착 지점 고정
- UAV 속력 제한
- 고도는 channel gain에 영향을 주므로 고려 안함

## 목적
- 처리율의 최솟값의 최대화 (전체 처리율도 고려)
1. 경로 주어졌을 때 전송 전력 최적화
2. 전송 전력 주어졌을 때 경로 최적화
3. 처리율 최솟값의 최대화 (1+2 -> 3) 
