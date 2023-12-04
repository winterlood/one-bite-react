“한 입 크기로 잘라먹는 리액트” 도서 및 강의에서는  
간단한 자바스크립트 코드를 실습하기 위해 **CodeSandBox**라는 온라인 에디터를 이용합니다.  
도서 및 강의에서도 CodeSandBox의 사용법을 자세히 다루고 있습니다.

그러나 23년 11월 부터 **CodeSandBox**의 UI가 지속적으로 변경되면서  
독자 및 수강생 여러분들이 많은 불편함을 겪으실 것으로 예상됩니다.  

따라서 이러한 불편 사항들을 해소하기 위해 본 문서를 남겨두었으니  
문서를 참고하시어 CodeSandBox를 통해 실습을 잘 진행하셨으면 좋겠습니다.

## 01. CodeSandbox 계정 생성하기

23년 11월 부로 게스트(계정을 생성하지 않은 유저)의 권한이 대폭 축소되었습니다.  
따라서 원활한 실습을 위해 계정 생성이 필요합니다.

계정 생성을 위해 codesandbox.io로 접속하신 다음  
아래 그림에 빨간색 박스로 표시된 "Sign in" 버튼을 클릭합니다.

![image](https://github.com/winterlood/one-bite-react/assets/46296754/b2866c9c-82bb-41ba-bdd1-173934be72c5)

그럼 회원가입 및 로그인 화면이 나타납니다.  
여기서는 아무 방법이나 선택하셔도 상관없습니다.
<img width="1238" alt="image" src="https://github.com/winterlood/one-bite-react/assets/46296754/c525512b-3ce7-4047-87eb-de70997b3037">

계정을 생성하고 로그인 하시면 아래와 같은 화면이 나타납니다.
<img width="1488" alt="image" src="https://github.com/winterlood/one-bite-react/assets/46296754/053b2530-5bc0-45b3-b021-ff0db2c89526">

## 02. CodeSandbox 설정 변경하기

이제 도서나 강의와 같인 환경에서 실습하기 위한 몇가지 환경 설정이 필요합니다.  
로그인 이후 나타나는 화면에서 왼쪽 위의 네모 박스 모양의 로고를 클릭해 메뉴 창을 연 다음  
Settings를 클릭합니다.

![image](https://github.com/winterlood/one-bite-react/assets/46296754/01881f50-b082-4646-947f-87c3dc9c46bb)


그럼 다음 그림과 같은 Settings 창이 나타납니다.  
여기서 좌측의 Experiments 탭을 클릭합니다.

![image](https://github.com/winterlood/one-bite-react/assets/46296754/8a12cae8-bb17-4cde-bbfd-4271fe3d707c)

여기서 Sandbox beta editor 옵션의 스위치를 아예 꺼 주시면 됩니다.  
그럼 다음과 같이 왜 beta editor를 사용하지 않을 것인지 이유를 묻습니다.  
원하시는 답을 선택하신 다음 Disable 버튼을 클릭하시면 됩니다.

![image](https://github.com/winterlood/one-bite-react/assets/46296754/56fd54b7-fa5b-45f1-a637-483b9069e420)

Disable 버튼을 클릭하시면 beta editor가 비활성화 됩니다.  
참고로 Disable 버튼을 클릭했음에도 UI상으로는 스위치가 안 꺼질 수 있습니다.   
그럴 때에는 클릭하신 다음 Settings 패널을 종료하셨다가 다시 열어보시면 꺼져있을 수 있습니다. 

![image](https://github.com/winterlood/one-bite-react/assets/46296754/484cef6b-bede-4a33-a2db-c24be14faaff)

여기까지 설정해 주셨다면 모두 완료되었습니다.  
이제 설정한 옵션이 잘 적용되도록 하기 위해  
새로고침을 2-3회 정도 진행하시거나 브라우저를 아예 껐다가 다시 켜시기 바랍니다.

## 03. 새로운 SandBox 생성하기

이제 새로운 Sandbox를 생성하여 실습을 진행할 수 있습니다.  
여러분의 원활한 실습 환경을 위해 템플릿을 만들어 두었는데요  
아래 링크로 접속하실 수 있습니다.  
[한입 크기로 잘라먹는 리액트 Sandbox 템플릿](https://codesandbox.io/s/han-ib-keugiro-jalrameogneun-riaegteu-vanila-js-template-p8kdf0)

위 링크로 접속하시면 페이지 우측 상단에 **Fork** 라는 파란색 버튼이 나타납니다.  
여기서 Fork란 쉽게 말해 "이 템플릿을 사용해 실습 환경을 구축하겠다" 라고 이해하시면 됩니다.  
이 Fork 버튼을 클릭한 다음 자신의 계정을 선택합니다.  
<img width="1158" alt="image" src="https://github.com/winterlood/one-bite-react/assets/46296754/ffaaf728-2134-4dc6-a715-8399f456d1a1">

그럼 다음과 같이 페이지 우측 하단에 "Forked Sandbox"라는 메세지가 나타납니다.    
<img width="1163" alt="image" src="https://github.com/winterlood/one-bite-react/assets/46296754/46894fd8-0bbf-437b-9406-c35b17f75a27">

이때 브라우저를 한번 **새로고침** 해 주시면 템플릿을 이용한 실습 환경 구축이 완료됩니다.  
자바스크립트 코드를 작성한 다음 console 탭을 열어서 확인해보세요  

<img width="1164" alt="image" src="https://github.com/winterlood/one-bite-react/assets/46296754/10a347ee-d2fe-401e-9cc8-8e58ebb52d54">

이제 강의나 도서의 설명에 따라 실습을 진행하시면 됩니다.  
행복한 프로그래밍이 되시길 바랍니다.  



