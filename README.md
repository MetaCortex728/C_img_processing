# C-Based Image Processor

![image](https://user-images.githubusercontent.com/22307448/142989076-8d93b180-4fd3-4e7d-84f6-9fdfcfbb8b1b.png)

C를 기반으로한 흑백 raw 이미지 처리 툴 입니다.
cmd에서 동작하며 이미지의 픽셀값을 2D Array에 저장후 포인터를 사용해 reference후 처리하는 방식입니다


This is a C-based image viewer/editor.
Run in cmd, images' pixel values are saved in a 2D-array which are referenced by pointers.
Required memory spaces are allocated by malloc() from the <stdlib.h> library.
The application supports basic image editing by adjusting pixel values and transposing arrays.



## Supported Functionalities

### I/O
- 저장
- 연속 처리


### 보정
- 밝기 조절
- 레벨링
- 필터링


| <img src="C:\IMG_PROJECT\P1_C\temp.jpg" alt="temp" style="zoom: 67%;" /> |
| ------------------------------------------------------------ |
| ![image](https://user-images.githubusercontent.com/22307448/142996252-9bc0bf1b-12c6-4103-8453-dbba58e657c3.png) |
| ![image](https://user-images.githubusercontent.com/22307448/142996285-c2c12f87-ac17-410d-bce6-06775b0a00c6.png) |










### Geometry
- 회전
- 플립
![image](https://user-images.githubusercontent.com/22307448/142996198-11eb1950-ac77-455b-bc93-e74e89ca3dc1.png)
![image](https://user-images.githubusercontent.com/22307448/142996220-c6a6d45a-dfc0-4273-b9a1-f33705a46066.png)



### ASCII Art
![image](https://user-images.githubusercontent.com/22307448/142996147-7fdb05b5-e028-4ee6-9771-c11d04dd1de5.png)
![image](https://user-images.githubusercontent.com/22307448/142996172-f27c0f02-9ff7-464f-b5b9-e81f6ef7bed3.png)



## Notes
_저수준 제어가 가능한 이미지 처리 기능구현이 프로그램의 목적입니다_
_다양한 확장자처리, 이미지 사이즈 핸들링 및 리사이징은 지원하지 않습니다_
_베이스 경로는 C:\images\raw512 입니다_

