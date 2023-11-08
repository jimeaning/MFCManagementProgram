<<<<<<< HEAD
# MFCManagementProgramProject

RFID 모듈을 사용한 MFC 방식의 음반 대여 프로그램

## 주요 부품
![](https://velog.velcdn.com/images/jimeaning/post/e26ebcab-aa47-4611-a080-248f85b8e97c/image.png)
- IS-3400 v3.0
- iso 14443 카드

<br>

## 프로그램 기능
### 작업 플로우
![](https://velog.velcdn.com/images/jimeaning/post/52891fe6-4ad2-4341-9368-8e1da532da69/image.png)

### 상세 구현 기능
#### RFID 연결 및 해제
- **RFID 연결** : RFID 연결이 성공되면 메시지가 출력된다.
  
![](https://velog.velcdn.com/images/jimeaning/post/71c7b27d-6dbd-41ff-8ce2-ef5b8da13886/image.png)

- **RFID 연결 해제** : ‘RFID 해제’ 버튼을 누르면 해제된다.
  
![](https://velog.velcdn.com/images/jimeaning/post/b24b577b-f22f-4594-95a0-7b12175596ae/image.png)

- **메인 이미지 출력** : 'BMP 이미지' 버튼을 클릭하면 메인 이미지가 출력된다.
  
![](https://velog.velcdn.com/images/jimeaning/post/fdc0fe4a-c739-4f87-a0ae-c34212d46731/image.png)

<br>

#### 대여 관리
- **앨범 읽기** : UID가 출력되고 앨범 이미지와 대여 가능 여부가 출력된다.
  - 대여가 가능할 때 ‘대여하기’ 버튼이 활성화된다
    
![](https://velog.velcdn.com/images/jimeaning/post/a1c39a85-20b4-485e-b279-4b58f8b7e0bd/image.png)
  - 이미 대여중이면 ‘대출중’이 표시되고, ‘대여하기’ 버튼이 비활성화된다.
    
  ![](https://velog.velcdn.com/images/jimeaning/post/e0d0ffca-96b5-4eab-a10d-dbb8f8b71737/image.png)
  
- **대여 신청** : ’대여하기‘ 버튼을 누르면 대여가 완료된다
#### 프로그램 종료
- **종료** : ’종료‘ 버튼을 누르면 프로그램이 종료된다
=======
# MFCManagementProgram
>>>>>>> 559d00181f46cf3c30062c355677a5d56275fddf
