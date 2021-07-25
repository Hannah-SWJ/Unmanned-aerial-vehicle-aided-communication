# Unmanned Aerial Vehicle-Aided Communications : Joint transmit Power and Trajectory Optimization
무인 항공기 통신의 전송파워와 이동 경로 최적화

## 상황
- UAV와 데이터를 주고 받는 노드들이 임의로 뿌려져 있는 상태
- UAV가 이동하면서 데이터를 전달 받음
- 순서 : 임의의 여러 노드가 hub 노드에게 데이터 전송 -> UAV 출발 지점에서 출발 -> hub를 돌면서 데이터를 받음 (hub 노드의 개수(=cluster 개수) 고정X) -> UAV 도착 지점에 도착

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



<임의의 노드>

![image](https://user-images.githubusercontent.com/59918820/126115274-7943ccb2-0eb7-4616-b951-01d8d23cf888.png)

<클러스터 개수 & hub 노드 표현>

![image](https://user-images.githubusercontent.com/59918820/126115361-1fe05f6c-4785-4f07-b73d-bc5b38cd29d0.png)

<노드 연결 상태>

![image](https://user-images.githubusercontent.com/59918820/126115596-d5515289-8f3c-4283-b3b8-0f4f0d8e9a16.png)

<행렬로 표현된 노드 연결 상태>

![image](https://user-images.githubusercontent.com/59918820/126115657-ea6dd18c-89fe-4bce-9611-a877e507918b.png)


