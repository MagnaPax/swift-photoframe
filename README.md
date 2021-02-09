# 사진 액자 앱

- 2021년 2월 8일 생성

- 코드스쿼드 마스터즈 iOS 코스



## STEP 1. Tabbed 앱

로컬에 "PhotoFrame" 프로젝트를 저장한다

- Tab Bar Controller 추가



![initial](https://user-images.githubusercontent.com/73650994/107309267-7644ea80-6acd-11eb-88ce-247b456e9971.png)



- ViewController 클래스 viewDidLoad() 함수에 `print(#file, #line, #function, #colum)` 코드를 추가한다

- 실행 후 콘솔 영역에 출력된 것을 확인한다



![initial](https://user-images.githubusercontent.com/73650994/107309393-b1dfb480-6acd-11eb-8ecc-c91d4033e54a.png)


---



## STEP 2. IBOutlet

- 레이블을 만들고 ViewController 코드에 IBOutlet으로 연결한다
- photoDescription 레이블도 마찬가지로 연결한다
- 레이블의 속성을 코드로 변경한다

![initial](https://user-images.githubusercontent.com/73650994/107325741-a1d7cd00-6aed-11eb-8002-0937ca308d1e.png)




----

## STEP 3. IBAction

- UIButton 추가 및 IBAction 연결
- propertyChangeButton 메소드에 레이블 속성 변화 기능 추가

- before Button touch

![initial](https://user-images.githubusercontent.com/73650994/107332622-bcaf3f00-6af7-11eb-968c-2373f9908a7e.png)

- after Button touch

![initial](https://user-images.githubusercontent.com/73650994/107332724-dfd9ee80-6af7-11eb-8255-6f6bebdacbb0.png)



----

## STEP 4. Scene과 Segue

-  ViewController 를 추가하고 연결해서 새로운 Scene을 추가한다
- Scene 연결 작업을 하며 Segue 실습해본다

![initial](https://user-images.githubusercontent.com/73650994/107338107-85905c00-6afe-11eb-8520-f74d1c6db811.png)

![initial](https://user-images.githubusercontent.com/73650994/107337719-10bd2200-6afe-11eb-82d8-94288015b018.png)

![initial](https://user-images.githubusercontent.com/73650994/107337737-161a6c80-6afe-11eb-886c-0910cf71419e.png)




---

## STEP 5. ViewController programming

- 새로운 viewController 추가 및 연결
- 화면 닫기 동작 (dismiss)

![initial](https://user-images.githubusercontent.com/73650994/107342338-6fd16580-6b03-11eb-8d65-d62617d0d80b.png)

![initial](https://user-images.githubusercontent.com/73650994/107342354-73fd8300-6b03-11eb-8b81-6b58d27eb41a.png)

- dismiss: 뷰 스택을 줄여주는 역할을 한다고 한다




----

## STEP 6. Containter ViewController

- Navigation Controller Embed
- close button revise

![initial](https://user-images.githubusercontent.com/73650994/107346061-9c877c00-6b07-11eb-9b13-0930d941addf.png)



---

## STEP 7. Second Scene

- Tab bar의 두번째 화면을 만들고
- UIImageView를 사용하여 이미지뷰를 익힌다

![initial](https://user-images.githubusercontent.com/73650994/107361085-28a29f00-6b1a-11eb-8c04-d301d17671cf.png)

![initial](https://user-images.githubusercontent.com/73650994/107361100-2fc9ad00-6b1a-11eb-9516-96c0adeccf0b.png)

- 이미지 뷰 속성 관리 : content mode
- aspect fill 을 사용 (원본 비율, UIImageView 화면에 꽉 참)

