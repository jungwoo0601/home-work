# 로그인창 과제 회고

## 회고

- github에 절대경로로 이미지를 불러들이면 잘린다고 하여, 상대경로로 넣어봤다. "../assets/images/unchecked.svg"로 바꿔넣었지만 이미지가 불러와지지 않았다. 불러오지 못하는 문제가 발생하자, 또 다른 대안인 ../을 두번사용하여 "../../assets/images/unchecked.svg" 이렇게 시도했더니 성공했다.

---

- stay-signed-in 클래스에서 라벨인 '로그인 상태 유지'를 어떻게 해야 부모박스의 오른쪽 끝으로 보낼지 고민했다. 처음에는 position:relative와 right:0을 사용하여 옮기려고 했지만 더 나은 방법을 찾기 위해 블로그들을 돌아보았다. 그 와중에 margin-left:auto; 라는 해당 요소가 가능한 모든 남은 공간을 밀어내게 된다는 것을 깨닫고 결국 "margin-left:auto"를 쓰게 되었다.

---

- 조건에서 'border와 padding을 rem으로 줘라'라고 달려있어서, 중간 조건에 '좌/우 여백을 20px로 줘라'라는 것에서 고민을 하였다. 그러다 결국 첫번째 조건인 rem으로 사용하기로 마음먹었다.

---

- 아직 가상요소에 대해 많이 부족하다는 것을 느꼈다. 어떻게 해야 stay-signed-in에서 label 앞에 이미지를 붙이지 고민하며, gpt에게 정보를 물어본 것으로 보아, 많이 익숙해질 필요가 있다고 느꼈다.

---

- 아래의 두개는 꼭 기억해두자. display: none, block을 통해 모바일과 데스크톱에서 모습을 감추거나 보이게 할수 있다는 것을.

.ip-security-area {
display: none;
}

.ip-security-area {
display: block;
}
