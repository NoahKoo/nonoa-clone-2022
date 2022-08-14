# Nonoa Clone 2022

HTML & CSS are so much fun!

1. friends.html 내용 중
   <div class="user-component__column">의 lastchild가 적용되어 이름부분이 제대로 나오지 않음
   -->  <main class="friends-screen">
        <div class="user-component">
        <div class="user-component__column">
          <img
            src="./img/구준호.JPG"
            class="user-component__avatar user-component__avatar--xl"
          />
          <div class="user-component__text">
            <h4 class="user-component__title">구준호</h4>
            <!-- <h6 class="user-component__subtitle">this is whatever</h6> -->
          </div>
        </div>
        <div class="user-component__column"></div> <-- 1개 더 만들어 해당 div가 적용받게 만들어 해결완료.
      </div>
