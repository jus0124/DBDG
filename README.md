# My SQL 과 Node.js를 활용한 온라인 쇼핑몰 제작

## 개요
My SQL을 활용하여 데이터베이스를 운용, Node.js를 활용한 온라인 서비스를 시도해 보았습니다. 


| 하드웨어 환경 | 소프트웨어 환경 |
| --- | --- |
| CPU : Ryzen 5 5700X <br><br>GPU : NVIDIA GeForce 2060 8GB <br>8Gbps(Memory Speed), Compute Capability 6.1 <br><br>Memory : 16GB, 2133MHz<br><br>저장장치 : HDD | My SQL ver 8.0 <br><br> Node.js ver 21 <br><br> |


## ER 다이어그램
<br>


## 게임 흐름도
<img src="img/001.png">

<br>

## 몬스터 패턴 원리 및 설명
유니티에서 제공하는 mathf()를 사용하여 도형을 구현하였습니다. 원하는 도형의 꼭짓점의 개수를 구하고, 360f에서 꼭짓점 수를 나누게 되면 각 꼭짓점 간의 각도를 구할 수 있습니다. 이를 A라고 가정합니다. 이후 각도 A를 라디안으로 변환 해야하는데, 반복문을 사용하여 각 꼭짓점에 ‘A*Mathf.Deg2Red’를 사용하면 B라는 라디안이 나오게 됩니다. 원의 방정식인 ‘x = Mathf.Cos(B) * 반지름’, ‘y = Mathf.Sin(B) * 반지름’를 이용하여 (x, y)를 구한뒤 ‘vector2(x, y)’를 통해 총알 위치를 설정하면 다양한 탄막을 구현 할 수 있습니다. 


<br>
<center><몬스터 탄막 패턴><center>
<img src="img/002.png" width="350">

<img src="img/003.png" width="350">

<img src="img/004.png" width="350">




## 스크린샷 및 상세 설명

<img src="img/005.png" width="350">

메인화면입니다.

<img src="img/006.png" width="350">

인 게임 화면입니다. 마우스 위치에 십자선이 위치하고 마우스 좌클릭 시 총알이 나갑니다.

<img src="img/007.png" width="350">

일시정지 화면입니다.

<img src="img/008.png" width="350">

상점 화면 입니다.

<img src="img/009.png" width="350">

전투 화면 입니다. 몬스터의 머리를 맞추면 데미지를 입습니다.
