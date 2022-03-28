# 엑스퍼트 아카데미 리뉴얼 프로젝트
<br/>

## 새싹디벨로퍼 팀원
[미연](https://github.com/kalmtalyst) 
[세영](https://github.com/julie-kim-dev) 
[한솔](https://github.com/hansol787897465121) 
[예지](https://github.com/yeahhaaa) 
[승연](https://github.com/devSeung0v0)
[여진](https://github.com/yeojincho)
<br/>
<br/>
<br/>

## 프로젝트 목적
엑스퍼트아카데미 웹사이트 디자인&메뉴 개선, 반응형 웹 구축 등 사용자의 편의성 제공을 위한 홈페이지 리뉴얼 프로젝트 <br/>
[Notion](https://www.notion.so/Sesac-1c656fd978fd4196b04fb7728cb26293)
  <div >
<img width="800" alt="엑스퍼트 웹사이트 구조" src="https://user-images.githubusercontent.com/86069422/160288239-68dedfbc-0881-42a2-8e3f-c06536b316bd.png">
<img src="https://user-images.githubusercontent.com/86069422/160289118-1d22d280-9e8c-4abd-bcce-61477758457a.png" width="200"/>
  
  </div>
<br/>
<br/>

## 기술 스택

  ![](https://img.shields.io/badge/-react-blue?logo=React)
  ![](https://img.shields.io/badge/-JavaScript-yellow?logo=JavaScript)
  ![](https://img.shields.io/badge/-jQuery-green?logo=jQuery)
  ![](https://img.shields.io/badge/-CSS-orange?logo=CSS3)
  ![](https://img.shields.io/badge/-VScode-red)
  ![](https://img.shields.io/badge/-Figma-blueviolet?logo=Figma)
<br/><br/><br/>

## 설치 패키지
```
npm install axios
npm install react-router-dom@5
npm install redux react-redux
npm install reactstrap
npm install bootstarp
npm install swiper
npm install jquery
npm install react-responsive
npm install react-scroll
npm install react-cookie
npm install react-draggable
npm install --save react-daum-postcode 
```

## 개발내용
총 6명의 팀원으로 구성되어 프로젝트를 진행하였습니다. 이 6명 모두 디자인 단계부터 함께 참여했으며, 개발 과정에서도 끊임없는 대화를 나누었습니다. 기술적으로 해결할 수 있는 문제와 그렇지 않은 문제에 대해 함께 논의하며 서비스를 발전시켰습니다. 한정된 시간이 주어진 상태에서 거의 디자인부터 시작하여 어려움이 많았지만 단순히 디자인을 구현하는것이 아닌, 사용자경험을 개선하여 서비스의 비즈니스를 이해하고 재사용성이 높은 코드를 담으려 노력하였습니다. 
<br/><br/>

## 변경사항

<details>
<summary> Before / After </summary>
<div markdown="1">
  
    |기존 홈페이지|리뉴얼 홈페이지|
|:-:|:-:|
|[기존 홈페이지 바로가기](http://www.excacademy.co.kr/)|[리뉴얼 홈페이지(클릭 혹은 QRcode)](http://expert002.cafe24.com/)|
|![기존 홈페이지](https://user-images.githubusercontent.com/86069422/160289411-564c3b27-dd5b-497a-8f6f-98bd0ca8de34.png)|![리뉴얼 홈페이지](https://user-images.githubusercontent.com/86069422/160289403-dce6064d-75b5-4668-a56d-88ebef30ba16.png)|
|![기존 홈페이지](https://user-images.githubusercontent.com/86069422/160289555-1ee62272-7c95-4c86-b8b2-5b5a182454a0.png)|![리뉴얼 홈페이지](https://user-images.githubusercontent.com/86069422/160289560-99a1851c-7af1-4a28-93e6-42bbab8ff2b7.png)|
|![기존 홈페이지](https://user-images.githubusercontent.com/86069422/160290095-85b481db-e5d1-46ae-97f0-3655c2fae262.jpeg)|![리뉴얼 홈페이지](https://user-images.githubusercontent.com/86069422/160287960-a890546d-580d-44d0-b05a-3060499e0506.gif)|
 
</div>
</details>




<details>
<summary>강사소개</summary>
<div markdown="1">
<p>
  
<img src="https://user-images.githubusercontent.com/86069422/160338347-67fa8441-80d3-48c3-a785-c512495d9c0f.gif" width="800" height="400"  >
</p>
<div>
<p>:one: 버튼 클릭시 인터뷰 영상 연결</p>

```
버튼 클릭시 window.open()으로 강사 인터뷰 영상 url을 새탭으로 열기 
```
<p>:two: 강의 선택시 이동하기</p>

```
select의 각 option에 value값으로 해당 path값을 주어 선택시 window.location.href = value; 로 강의 상세 페이지 이동
```

</div>
</div>
</details>

<details>
<summary>회원정보관리</summary>
<div markdown="1">
<p>
  
<img src="https://user-images.githubusercontent.com/86069422/160338344-fde9e0c5-10b2-4572-b552-fbf2cf827da2.gif" width="800" height="400"  >
</p>
<div>
<p>:one: 회원구분 - 교육담당자 option 선택시</p>

```
부가정보2 의 모든 input태그 필수입력(안내문구 노출), 
```
<p>:two: 주소검색 기능</p>

```
주소검색 후 선택한 주소값이 input태그의 value값으로 남게 된다.
```
<p>:three: 확인팝업</p>

```
회원정보가 수정되었음을 알리는 확인팝업
```

</div>
</div>
</details>

<details>
<summary>비밀번호 변경</summary>
<div markdown="1">
<p>
  
<img src="https://user-images.githubusercontent.com/86069422/160338343-787a5e4a-ff96-4606-b628-50ac9791c27f.gif" width="800" height="400"  >
</p>
<div>
<p>:one: 비밀번호 유효성검사 </p>

```
비밀번호 유효성검사
```
<p>:two: 확인 팝업</p>

```
비밀번호 변경확인 팝업
```
<p>:three: 변경완료 후 페이지 이동</p>

```
비밀번호 변경 팝업 확인 클릭시 회원정보관리 페이지로 이동
```

</div>
</div>
</details>

<details>
<summary>수강신청 확인/취소</summary>
<div markdown="1">
<p>
  
<img src="https://user-images.githubusercontent.com/86069422/160338335-20198ea4-33f1-4e23-a052-76aa2e32c671.gif" width="800" height="400"  >
</p>
<div>
<p>:one: 수강신청 취소  </p>

```
신청취소 버튼 클릭시 선택 과정 취소 팝업, 선택한 수강신청 내역이 삭제
```
<p>:two: 수강신청 내역 없음 안내</p>

```
수강신청 내역이 없거나 모두 삭제된 경우 안내 문구 출력
```

</div>
</div>
</details>

<details>
<summary>수강내역</summary>
<div markdown="1">
<p>
  
<img src="https://user-images.githubusercontent.com/86069422/160338324-801f0e02-fda7-4a52-8d05-0c3b13c8233a.gif" width="800" height="400"  >
</p>
<div>
<p>:one: 수강내역 </p>

```
수강한 내역 확인
```
<p>:two: 수료증 다운로드 </p>

```
수료증 다운로드 버튼 클릭시 다운로드 완료 팝업
```

</div>
</div>
</details>

<details>
<summary>회원탈퇴</summary>
<div markdown="1">
<p>
  
<img src="https://user-images.githubusercontent.com/86069422/160339880-af11fca7-46cd-4702-b6fc-fbe79b4dfcff.gif" width="800" height="400"  >
</p>
<div>
<p>:one: 회원탈퇴 버튼 </p>

```
회원정보관리 페이지 맨아래 색상없이 흰색 버튼으로 눈에 덜 띄도록 적용
```
<p>:two: 탈퇴하기 버튼 클릭 </p>

```
탈퇴하기 버튼 클릭시 로그아웃 상태로 메인 페이지로 이동
```

</div>
</div>
</details>






