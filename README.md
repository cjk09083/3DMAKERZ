# 3DMAKERZ
<div>
<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
<img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=PHP&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
</div>

## 3DMAKERZ 경매 프로젝트 (Web,  Kiri:Moto)


## 목적
- 사용자가 3D 프린터의 도면을 경매에 올리면 파트너사들이 가격, 납품일을 입력해서 경매에 참여
- 경매, 결제, 제작 진행을 공유하는 관리 페이지 

## 담당
- 디자인, 웹퍼블리싱 제외 1인개발

## 기능 : 올메이크
### 고객이 제작 도면을 업로드하고 견적을 문의하는 사이트
- 절삭 / 레이저 / 3D프린팅 중 가공 방법 선택
<div align="center" >
<img src="ScreenShot/2.%20제작%20-%20도면보유.png" width="100%"/>
</div></br>

- 3D 프린팅 선택 시 도면을 업로드해서 소요시간과 가격을 미리 점검
- 소요시간과 가격 계산을 위해 <a href ="https://grid.space/kiri/"><b>Kiri:Moto</b></a> API 사용
<div align="center" >
<img src="ScreenShot/2-3.%20제작%20-%203D프린팅.png" width="100%"/>
</div></br>

## 기능 : 관리 페이지
### 입찰 관리
- 클라이언트가 시작한 입찰 대기 항목들을 보고 파트너사가 입찰
- 클라이언트가 입찰 내역들중 하나를 선택하면 입찰이 완료
<div align="center" >
<img src="ScreenShot/관리자페이지/1-2.%20입찰중.png" width="100%"/>&nbsp;
<img src="ScreenShot/관리자페이지/1-1.%20입찰보기%20(중단).png" width="100%"/>&nbsp;
</div></br>

### 주문&결제 관리
- 입찰완료된 항목은 진행 상황에 따라 주문 & 결제 정보가 연동
<div align="center" >
<img src="ScreenShot/관리자페이지/2.%20주문%20관리.png" width="100%"/>&nbsp;
</div></br>

### 회원 관리
- 클라이언트의 회원정보와 주문내역 관리
<div align="center" >
<img src="ScreenShot/관리자페이지/4-1%20주문내역.png" width="100%"/>&nbsp;
</div></br>

- 파트너사의 회원정보와 정산내역 관리
<div align="center" >
<img src="ScreenShot/관리자페이지/5.%20파트너%20관리.png" width="100%"/>&nbsp;
</div></br>
