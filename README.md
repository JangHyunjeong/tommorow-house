# 내일의집

### 1.GNB

- 로그인을 하지 않은경우

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="검색 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>
  <a
    href="/"
    class="gnb-icon-button is-cart"
    arial-label="장바구니 페이지로 이동, 999개의 상품이 장바구니에 담겨있습니다."
  >
    <i class="ic-cart"></i>
    <strong class="badge">999</strong>
  </a>
  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```

- 로그인을 했을 경우

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="검색 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>
  <a
    href="/"
    class="gnb-icon-button sm-hidden"
    arial-label="스크랩북 페이지로 이동"
  >
    <i class="ic-bookmark"></i>
  </a>
  <a
    href="/"
    class="gnb-icon-button sm-hidden"
    arial-label="내소식 페이지로 이동"
  >
    <i class="ic-bell"></i>
  </a>
  <a
    href="/"
    class="gnb-icon-button is-cart"
    arial-label="장바구니 페이지로 이동, 999개의 상품이 장바구니에 담겨있습니다."
  >
    <i class="ic-cart"></i>
    <strong class="badge">999</strong>
  </a>
  <button
    class="gnb-avatar-button sm-hidden"
    type="button"
    aria-label="마이메뉴 열기 버튼"
  >
    <div class="avatar-32">
      <img src="./assets/images/img-user-01.jpg" alt="사달라아저씨" />
    </div>
  </button>
</div>
```

### 2. 해상도 별 class

| mobile | tablet | desktop | class      |
| ------ | ------ | ------- | ---------- |
| O      | X      | X       | .sm-only   |
| O      | O      | X       | .lg-hidden |
| X      | X      | X       | .md-only   |
| X      | O      | O       | .sm-hidden |
| X      | X      | O       | .lg-only   |
| O      | X      | O       | .md-hidden |
