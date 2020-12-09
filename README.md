


## 개요
2020년도 2학기 스마트 IOT 캡스톤디자인 프로젝트 관리 페이지입니다.
## 팀
- 팀명 : **스마트임베디드**
- 팀원 및 역할
    - 강준영 : 프로젝트 진행 총괄 & 보고서 작성 & git 관리  & 서류작성 및 물품구매 관리 & 아두이노 소스코드 제작 및 보완 & 앱 인벤터 제작 & 중간, 결과보고서 작성
    - 박성중 : 아두이노 소스코드 제작 및 보완 & 소스코드 제작 및 보완 & 보고서 작성
    - 김경빈 : 라즈베리파이 카메라 모듈 제어 및 VNC Viewer 어플을 이용한 데이터 송수신 & 보고서 작성
    - 김민석 : 하드웨어 제작 & 보고서 작성 & 테스팅(시나리오, 성능측정) 
    - 이지나 : 하드웨어 제작 & 보고서 작성 & 테스팅(시나리오, 성능측정) & 발표자료 ppt 제작
    
## 주제 및 기대효과
  - 프로젝트명 : **AutoFeed**
  
  - 프로젝트 내용 :
    - 아두이노를 이용하여 자동 배급기를 제작한다. RTC모듈을 이용하여 실제 시간을 아두이노 내에 업로드하고, 알람 시간을 설정한다.
    - 설정한 알람 시간이 모터가 돌아가서 일정량의 사료가 자동으로 공급된다. 로드셀을 이용하여 공급된 사료의 무게를 측정하므로, 보다 정확한 양의 사료를 공급할 수 있다.
    - 사료 공급이 완료되면 부저가 울리게 되고, 모터의 동작을 멈춘다.
    - 초음파 센서를 이용하여 사료통 내부의 사료양을 측정하고, 블루투스를 이용한 시리얼 통신으로 사용자의 스마트폰으로 값을 보낸다. 그리고 그 값에 따라 남은 사료의 유무를 판단하는 어플을 제       작한다.
    - 라즈베리파이를 이용하여 카메라모듈을 동작시켜 제품이 잘 동작되고 있는지 확인 하도록 설계한다. 포트포워딩을 통한 외부 ip를 이용하므로 언제 어디서든 반려동물을 관찰할 수 있다.
  
  - 기대효과
    - 일정 시간이 되면 자동으로 사료가 나오므로 일일히 사료를 챙겨줄 필요성을 덜 수 있다.
    - 로드셀을 이용한 무게측정으로, 기존 제품들에 있던 사료 공급량의 오차를 최소화 할 수 있다.
    - 부저를 이용하여 반려견이 식사 시간임을 인지하도록 할 수 있다.
    - 카메라 모듈을 이용하여 멀리서도 반려견이 식사를 잘 하고 있는지 볼 수 있고, 이로 인해 오래동안 집을 비울 때도 안심할 수 있다.
    - 시리얼 통신으로 전송된 초음파 센서의 측정값을 확인하여 남은 사료의 양을 효율적으로 체크할 수 있다.
    - 시리얼 통신으로 전송된 초음파 센서의 측정 데이터를 어플로 보내고 사료가 모자라면 경고문과 경고 녹음 메세지가 출력되어 일일이 남은 사료양을 측정 할 필요가 없다.
   바쁜 현대인들의 삶을 생각해 볼 때, 이 제품을 사용한다면 일과 약속에 지장이 생기는 것을 방지할 수 있고 반려동물들의 건강을 더욱 스마트하고 편리하게 관리할 수 있다.
   
## 개발 환경

  - Raspberry Pi 3B+
  - Arduino UNO R3 
  - MIT App inventor2
  
## 전체적인 구성도
- 첫 번 째 아두이노

![image](https://user-images.githubusercontent.com/71344823/94539919-d2c30e00-0280-11eb-9185-7e7012eeb095.png)

![Mainboard회로도](https://user-images.githubusercontent.com/71344823/100964131-4af0cd00-356b-11eb-8bce-d8b354b61e39.jpg)





-두 번째 아두이노

![image](https://user-images.githubusercontent.com/71344823/96357282-e8677d00-1134-11eb-9c2b-0fb40999b85d.png)

![앱인벤터회로도](https://user-images.githubusercontent.com/71344823/100964162-5cd27000-356b-11eb-985b-52044c030def.jpg)





-라즈베리파이

![image](https://user-images.githubusercontent.com/71344823/94540017-ef5f4600-0280-11eb-817a-41a7058ca417.png)

## 플로우 차트
- 첫 번째 아두이노                 
<img width="173" alt="아두이노1 플로우차트" src="https://user-images.githubusercontent.com/71344823/100492984-d0443e00-3175-11eb-9968-98a6d7cb7911.PNG"> 
- 두 번째 아두이노
<img width="257" alt="아두이노 2 플로우차트" src="https://user-images.githubusercontent.com/71344823/100492994-e8b45880-3175-11eb-8bce-ad49d1ba6061.PNG">
- 라즈베리 파이
<img width="144" alt="라즈베리파이 플로우차트" src="https://user-images.githubusercontent.com/71344823/101615269-450a5880-3a51-11eb-932c-e7f3d5b986f8.PNG">





## 보고서 
[캡스톤디자인_신청서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5276358/_.docx)

[캡스톤디자인_부품회의_9월22일.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5276366/_._9.22.docx)

[9월 29일 캡스톤 디자인 활동보고서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5297822/9.29.docx)

[9월 29일 회의내용.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5297820/9.29.docx)

[10.13 캡스톤 디자인 활동 보고서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5458766/10.13.docx)

[10.27 캡스톤 디자인 활동보고서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5458767/10.27.docx)

[10월 29일 활동 보고서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5458770/10.29.docx)

[2020스마트IoT캡스톤디자인 포스터 양식_수정본.pdf](https://github.com/JUNYOUNG96/AutoFeed/files/5458771/2020.IoT._.pdf)

[2020스마트IoT캡스톤디자인 포스터 양식_수정본.pptx](https://github.com/JUNYOUNG96/AutoFeed/files/5458773/2020.IoT._.pptx)

[11월 9일 활동 보고서(소프트웨어).docx](https://github.com/JUNYOUNG96/AutoFeed/files/5506494/11.9.docx)

[11.9 활동보고서_하드웨어.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5610015/11.9._.docx)

[11.9 활동보고서_라즈베리파이.pdf](https://github.com/JUNYOUNG96/AutoFeed/files/5610026/11.9._.pdf)

[11월 24일 캡스톤 디자인 활동 보고서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5610014/11.24.docx)

[스마트임베디드_포스터.pdf](https://github.com/JUNYOUNG96/AutoFeed/files/5633666/_.pdf)

[스마트임베디드_포스터.pptx](https://github.com/JUNYOUNG96/AutoFeed/files/5633667/_.pptx)

[캡스톤디자인_결과보고서.docx](https://github.com/JUNYOUNG96/AutoFeed/files/5665056/_.docx)



### 회의록 

[스마트 임베디드 회의록.pdf](https://github.com/JUNYOUNG96/AutoFeed/files/5610027/default.pdf)


### 참고 문서

-앱인벤터 사용법
https://m.blog.naver.com/PostView.nhn?blogId=kindpark6142&logNo=221028648588&proxyReferer=https%3A%2F%2Fwww.google.co.kr%2F

-피에조 부저 사용법
https://codingrun.tistory.com/104?category=674346

-로드셀 참고
https://m.blog.naver.com/PostView.nhn?blogId=roboholic84&logNo=220441853297&proxyReferer=https:%2F%2Fwww.bing.com%2F

-RTC 참고
https://turtleshell.kr/88

-블루투스 모듈 참고
http://blog.naver.com/PostView.nhn?blogId=eduino&logNo=221121406317

-초음파 센서 참고
https://www.kocoafab.cc/tutorial/view/65

-LCD 모듈 참고
https://kocoafab.cc/tutorial/view/733

-라즈베리파이 CCTV 참고
http://www.3demp.com/community/boardDetails.php?cbID=233

### 추진 계획
 - 팀원들 각각에게 소프트웨어, 하드웨어, 라즈베리파이 파트를 정해준다. 코로나로 인해 자주 만나기 힘들기 때문    에 각자 맡은 파트를 진행하고 1주일에 한 번 씩 줌으로 진행 현황을 보고한다.
 - 2주에 한 번 씩 교수님과 함께 단체 미팅을 진행하고, 합을 맞춤으로써 앞으로의 진행 방향을 토론한다.
 
### 결과
 - 처음 계획했던 대로, 1주 혹은 2주에 한번씩 정기적인 모임을 가져서 프로젝트를 진행했다. 기존에 있던 제품들의 단점들을 보완하는 방식으로 프로젝트를 진행하였고, 그 내용은 
    1. 로드셀을 이용한 보다 정확한 양의 사료 공급
    2. 초음파 센서를 이용한 남은 사료 양을 알려주는 어플 제작
    3. 사고 방지 및 사용자의 안심을 위한 원격 CCTV 제작
    이었고, 위의 기능들을 모두 지원하는 제품 제작에 성공하였다.
