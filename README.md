# 🍻 소비활동 데이터 수집 서비스


소비활동 데이터 수집 서비스는 주류 박람회에서 소비자들이 편리하게 주류 상품을 주문할 수 있고, 그에 따른 주류 소비 활동 데이터를 수집하는 서비스입니다. 소비자들은 이 웹서비스를 통해 박람회의 주류 상품 목록, 상품정보를 확인하여 구매하고자 하는 상품들을 주문할 수 있습니다. 결제 절차 없이 주문 후 발급되는 주문번호를 통해 부스에서 빠르게 결제 및 상품픽업이 가능합니다. 팡매자는 판매 상품 등록, 수정과 함께 부스의 주문 내역을 확인하여 주문 상품을 전달하고, 픽업 완료 처리로 편리한 상품 판매 관리가 가능합니다. 소비자들의 연령, 성별, 지역 정보 등을 바탕으로 카테고리에 따른 주류 소비 데이터를 수집할 수 있습니다.

</br>

## 팀원
경제학과 2017110922 이상민</br>
컴퓨터공학전공 2019112587 김지현</br>
정보통신학전공 2019112132 박수련</br>
컴퓨터공학전공 2019111991 안도영</br>

</br>

## ⚙️ 기술 스택

<br />

<div align=center>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
<img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
<img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white">
<img src="https://img.shields.io/badge/React Router-CA4245?style=for-the-badge&logo=React Router&logoColor=white">
<img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
</div>

<br />

## 💡 주요기능
<br/>

## 메인페이지(슬라이드 배너)

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/d13bc2b3-7232-48dc-80b6-e822a4cd6bce"
            alt=""
          /><br /><sub><b>메인페이지(배너)</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 현재 행사중이거나 홍보중인 제품들을 메인페이지 맨 첫 화면에서 확인할 수 있습니다.
- 일정 시간마다 다음 카드로 넘어가며, 수동 조작도 가능합니다.

<br />

## 메인페이지(무한스크롤)

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/99cac5a2-bf7f-41d7-b4ab-77e572b414b3"
            height="400px;"
            alt=""
          /><br /><sub><b>메인페이지(무한스크롤)</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 처음 15개 상품 데이터를 보여주고 15개 상품의 끝까지 스크롤을 내리면 15개의 상품을 추가로 생성해서 보여줍니다.

<br />

## 검색 기능

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/6c70df82-288e-41aa-a5a4-0b8e77e1fb8a"
            height="400px;"
            alt=""
          /><br /><sub><b>검색 기능</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 상단 네비게이션바의 검색창을 통해 키워드로 상품 검색을 할 수 있습니다.

<br />

## 회원가입

<div align="center">
  <table>
    <tr>
      <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/e1350070-908f-45df-a734-65b96df46e1e"
            height="400px;"
            alt=""
          /><br/><sub><b>구매자 회원가입</b></sub><br />
      </td>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/a64278ed-846e-4506-88a4-e02feaf69232"
            height="400px;"
            alt=""
          /><br /><sub><b>판매자 회원가입</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 구매자, 판매자별로 나누어 회원가입이 가능합니다.
- 구매자의 경우 소비활동 데이터 수집을 위해 상별, 나이 등의 개인정보를 입력합니다.
- 판매자의 경우 부스 운영을 위한 부스명을 입력합니다.

<br />

## 로그인


<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/ea6f5933-205b-4793-984b-355819441325"
            height="400px;"
            alt=""
          /><br /><sub><b>로그인</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 회원가입과 마찬가지로 구매자, 판매자별로 나누어져 있으며, 회원가입 시 입력한 아이디와 비밀번호로 로그인합니다.
- 로그인 후에 장바구니, 주문, 상품등록, 상품정보 수정 등의 기능을 기용 가능합니다.

<br />

## 상품 상세 페이지

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/3f8e215e-35f6-4918-888e-1861bf324032"
            height="400px;"
            alt=""
          /><br /><sub><b>상세페이지(구매자 계정)</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 상품목록에서 특정 상품을 클릭하명 해당 상품의 상세페이지로 이동합니다.
- 로그인하면 상품을 장바구니에 추가하거나 바로구매가 가능합니다.
- 판매자 계정으로 로그인 한 경우에는 바로구매와 장바구니 버튼이 비활성화 됩니다.

<br />

## 장바구니 페이지

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/5042ad51-fd42-4359-9543-88fd52315923"
            height="400px;"
            alt=""
          /><br /><sub><b>장바구니페이지</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 장바구니에 담은 상품들 목록 및 정보(상품명, 수량)을 확인 가능하며 전체 상품 또는 원하느 상품만 선택하여 주문할 수 있습니다.

<br />

## 주문 페이지

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/408928a7-d6f2-4aa5-b529-41d13cec4c04"
            height="400px;"
            alt=""
          />
      </td>
    </tr>
  </table>
</div>

- 이름, 전화번호 등의 정보를 입력 후 정보 제공 방침에 동의하면 주문 버튼이 활성화됩니다.
- 주문을 완료하면 주문 번호와 함께 상품을 수령할 수 있는 부스 번호가 표시됩니다.
  
<br />

## 주문 확인 기능

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/b02dd5b0-dca4-4dbe-812c-646269eaef61"
            height="400px;"
            alt=""
          /><br /><sub><b>주문 확인 기능</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 구매자는 상단 네비게이션 바의 마이페이지 버튼을 통해 그동안의 주문 내역들을 확인할 수 있습니다.
- 주문 일자, 주문 번호, 픽업 상태, 결제금액을 확인 가능하며 주문상세 버튼을 통해 주문의 상세정보(상품명, 수량 등)을 확인할 수 있습니다.

<br />

# 판매자 기능
## 상품등록

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/d34465ee-b49c-458d-a6ca-4506303fa489"
            height="400px;"
            alt=""
          /><br /><sub><b>상품등록(판매자 계정)</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- **상품등록은 판매자 계정으로 로그인 했을 경우에만 가능합니다**.
- 이미지 영역에서 **첨부 아이콘을 클릭**하고 등록할 상품의 이미지를 선택하면 **상품의 이미지가 미리보기로 나타납니다**.
- 나머지 정보들(상품명,판매가,재고)도 입력 후 저장하기 버튼을 통해 새 판매 상품을 등록할 수 있습니다.

<br />

## 판매자 대시보드

<div align="center">
  <table>
    <tr>
       <td align="center">
          <img
            src="https://github.com/AhnDo0/silhum/assets/51705063/702a5c9c-37fe-48c5-8769-f5c5c1e73126"
            height="400px;"
            alt=""
          /><br /><sub><b>판매자 대시보드</b></sub><br />
      </td>
    </tr>
  </table>
</div>

- 판매자는 해당 부스에 들어온 주문을 리스트의 형태로 확인하여 픽업 상품을 준비할 수 있습니다. 현장에서 결제 및 픽업이 완료된 경우 대시보드  각 주문에 있는 결제완료 버튼을 눌러 주문 상태를 처리할 수 있습니다.

<br />


