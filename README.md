# Vaccine reservation program

# 산업기사 문제 풀이과정1)
1)<br>
haeder nav section footer 페이지와<br>
홈화면 index <br>
백신예약 화면 join 그리고 DB로 연결해줄 join_P<br>
백신예약조회 화면 lookup 그리고 결과값을 출력해줄 lookup_P <br>
백신예약현황 화면인 status 페이지로 10페이지정도 되는것같다.<br>
2)<br>
테이블은 총 3개를 만들어야하며 tbl_jomin_202108, tbl_hosp_202108, tbl_vaccresv_202108 이있다<br>
문제지의 있는 데이터값을 sql를 통해서 넣어준후 join_p를 통해 추가 데이터값을 넣어준다<br>
DB연결<br>
![image](https://user-images.githubusercontent.com/96267331/201792920-e70dcaab-497c-498c-ae31-0a041d65c25e.png)<br>
index.jsp화면<br>
![image](https://user-images.githubusercontent.com/96267331/201790525-001149ea-f66b-41aa-9daf-07849e5918c7.png)<br>
haeder nav section footer jsp 파일을 한곳에 묶어 css를 입혀 만들어 준다.<br>
join.jsp 화면<br>
![image](https://user-images.githubusercontent.com/96267331/201790418-f3d7687c-0c0c-4f74-9d38-f729593c28af.png)<br>
form 태그안에 table태그를 통해서 데이터를 입력받을수있는 박스를 만들어준다. 
![image](https://user-images.githubusercontent.com/96267331/201813315-a2b551a0-8471-41d0-bfbf-c209cbd12cc5.png)<br>
그리고 만든 sql문을 이용하여 값을받은후 1을 더해 예약번호를 자동으로 입력받게한다.<br>
![image](https://user-images.githubusercontent.com/96267331/201792385-be154063-8273-4b7b-8e0e-b0244737e707.png)<br>
![image](https://user-images.githubusercontent.com/96267331/201792405-7da0503d-c0a3-47d7-b9e9-e22bab6e9d5e.png)<br>
등록버튼을 눌렀을때 유효성검사를 하며 만약 비어있는 부분이있으면 그 부분으로 포커스가간다.<br>
![image](https://user-images.githubusercontent.com/96267331/201813460-ceea7b4f-14fa-491c-98e3-affe99bac69a.png)<br>
join_P 등록하기<br>
![image](https://user-images.githubusercontent.com/96267331/201813657-9a134714-9b73-4d21-a8c5-2fccf109ffb3.png)<br>
join테이블의있는 박스의 값을 다 넣은 후 등록버튼을 누른다.<br>
![image](https://user-images.githubusercontent.com/96267331/201813745-a987d47f-fbae-401f-b885-596e9c3687f3.png)<br>
등록버튼을 누른 후에는 index페이지로 돌아가면서 데이터가 등록된다.<br>
![image](https://user-images.githubusercontent.com/96267331/201813777-4e3b154f-e7b5-44d6-994a-58c75434f47e.png)<br>
코드를 보면 박스에있는 값들을 형태의 맞게 sql문을 통해 DB테이블의 값을넣어주며 업데이트해준다.<br>
member_serch.jsp 화면
![image](https://user-images.githubusercontent.com/96267331/201845709-30648112-7058-43b8-8b96-ad55f82d1732.png)<br>
![image](https://user-images.githubusercontent.com/96267331/201846324-fc9a4066-56d4-4ac8-85df-31c0e7e9241c.png)<br>
유효성 검사기능도있다<br>
![image](https://user-images.githubusercontent.com/96267331/201846494-3c5aeb99-d2d9-4ad7-bf20-86cf2cc97dc8.png)<br>
만약 정보가있는 예약번호를 입력했을경우<br>
![image](https://user-images.githubusercontent.com/96267331/201845907-24423328-7a50-434d-be56-5bded45722d7.png)<br>
그 예약번호의 해당되는 정보들을 출력해주며 만약 없는 예약번호를 입력했을경우에는<br>
![image](https://user-images.githubusercontent.com/96267331/201846095-ee4c8ac2-737a-4f20-b48f-29304fab7eba.png)<br>
없는번호라고 출력해준다.
![image](https://user-images.githubusercontent.com/96267331/201846851-30898672-e2c2-4b74-a2d5-c5f08ed085ce.png)<br>
코드를 보면 sql문이 다양한 테이블에서 값을 가져와 값을 변화시켜주면서 출력해 <br>
![image](https://user-images.githubusercontent.com/96267331/201847050-f42e291e-8c9e-4b46-b1cb-52e0309cffed.png)<br>




