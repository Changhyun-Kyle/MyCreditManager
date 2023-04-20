# MyCreditManager(성적 관리 프로그램)
## `원티드 프리온보딩 iOS 챌린지 5월` - 사전과제
<img width="1032" alt="image" src="https://user-images.githubusercontent.com/101093592/233282146-1645e3e8-6e74-423e-a2c1-a0ec7f87b244.png">

## **프로젝트 이름**

- MyCreditManager

## 사용 언어 / 환경

- Swift
- Xcode 기본 템플릿 중 [macOS - Command Line Tool]

## **프로그램의 메뉴**

- 학생추가
- 학생삭제
- 성적추가(변경)
- 성적삭제
- 평점보기
- 종료

## **프로그램 동작조건**

- 사용자가 종료 메뉴를 선택하기 전까지는 계속해서 사용자의 입력을 받습니다
- 메뉴선택을 포함한 모든 입력은 숫자 또는 영문으로 받습니다

## 성적별 점수

- A+ (4.5점) / A (4점)
- B+ (3.5점) / B (3점)
- C+ (2.5점) / C (2점)
- D+ (1.5점) / D (1점)
- F (0점)

## 평점

- 각 과목의 점수 총 합 / 과목 수
- 최대 소수점 2번째 자리까지 출력
    - 예)
        - 3.75
        - 4.1
        - 2
        
## **프로그램 동작모습**

`예시 화면의 굵은 글씨는 콘솔 출력 내용이며, 얇은 글씨는 콘솔을 통한 입력 내용입니다.`

### **메뉴의 잘못된 입력 처리**

![image](https://user-images.githubusercontent.com/101093592/233283522-c873c0ea-48b0-45da-9939-49bece5b486a.png)

### **학생추가**

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 이미 존재하는 학생은 다시 추가하지 않습니다

![image](https://user-images.githubusercontent.com/101093592/233283617-7203e505-5113-43f4-904d-525bbf6c4bfa.png)

### **학생 삭제**

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 없는 학생은 삭제하지 않습니다

![image](https://user-images.githubusercontent.com/101093592/233283645-2d14fb8a-35b1-4ecc-8291-a60b37906b00.png)

### **성적추가**

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 없는 학생의 성적은 추가하지 않습니다

![image](https://user-images.githubusercontent.com/101093592/233283666-edc4601d-2658-4049-ab1b-e6dd9ab263d7.png)

### **성적삭제**

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 없는 학생의 성적은 삭제하지 않습니다

![image](https://user-images.githubusercontent.com/101093592/233283727-a98c5f0b-d287-45c2-815e-2b4496694556.png)

### **평점보기**

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 해당 학생의 과목과 성적을 모두 출력한 후 마지막 줄에 평점을 출력합니다
- 없는 학생은 평점을 보여주지 않습니다

![image](https://user-images.githubusercontent.com/101093592/233283753-3f58dbb1-b6cb-4c2d-80d9-4d25291469c6.png)

### **종료**

- 프로그램을 종료합니다

![image](https://user-images.githubusercontent.com/101093592/233283791-3673c723-f98c-4ad2-a18b-d39958ef9f8c.png)
