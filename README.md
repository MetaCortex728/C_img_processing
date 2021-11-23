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


### Geometry
- 회전
- 플립



### ASCII Art



## Notes
_저수준 제어가 가능한 이미지 처리 기능구현이 프로그램의 목적입니다_
_다양한 확장자처리, 이미지 사이즈 핸들링 및 리사이징은 지원하지 않습니다_


