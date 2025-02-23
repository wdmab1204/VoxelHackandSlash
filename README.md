**Main Works**

## A*를 이용한 실시간 최단거리 탐색
* 장애물 레이어를 기준으로 이동할 수 있는 노드와 없는 노드를 분간
* 우선순위 큐를 이용해 Open List 탐색 비용을 O(Log N)으로 단축
* 싱글톤 디자인패턴으로 모든 유닛에서 접근하기 쉬운 구조
* 스레드와 큐를 이용하여 작업요청을 비동기로 처리
* 블러 알고리즘을 응용하여 유닛들을 도로 가운데 이동으로 권장하도록 구현

[more](https://github.com/wdmab1204/QuadAction/tree/main/Assets/04%20Scripts/Unit/PathFinding)


## Object Pool 기법
* Pool클래스를 직렬화하여 인스펙터에서도 작업할 수 있는 구조
* tag를 기반으로 Pool Object를 가져올 수 있는 Dictionary를 응용한 기능 구현

[more](https://github.com/wdmab1204/QuadAction/tree/main/Assets/04%20Scripts/Unit/ObjectPool)


## MVC 디자인 패턴을 응용한 3D UI
* Model, View, Controller로 분류함으로 써 코드의 기능을 역할에 맞게 분류 및 가독성 향상
* 카메라의 Culling Mask를 이용해 3D UI 개발
* Model과 View의 변화가 생길 때 이벤트 함수 호출하여 변화에 대응

[more](https://github.com/wdmab1204/QuadAction/tree/main/Assets/04%20Scripts/UI/MVC)
