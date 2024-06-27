# Пример README

<div class="content">
  <div class="content__container">
    <p class="content__container__text">
      Hello
    </p>
    
    <ul class="content__container__list">
      <li class="content__container__list__item">world !</li>
      <li class="content__container__list__item">bob !</li>
      <li class="content__container__list__item">users !</li>
      <li class="content__container__list__item">everybody !</li>
    </ul>
  </div>
</div>

<style>
body {
  width: 100%;
  height: 100%;
  position: fixed;
  background-color: #34495e;
}

.content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  height: 160px;
  overflow:hidden;
  
  font-family: 'Lato', sans-serif;
  font-size: 35px;
  line-height: 40px;
  color: #ecf0f1;
}

.content__container {
  font-weight: 600;
  overflow: hidden;
  height: 40px;
  padding: 0 40px;
  position: relative;
}

.content__container:before {
  content: '[';
  left: 0;
  color: #16a085;
  font-size: 42px;
  line-height: 40px;
  position: absolute;
  top: 0;
  animation-name: opacity;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}

.content__container:after {
  content: ']';
  position: absolute;
  right: 0;
  top: 0;
  color: #16a085;
  font-size: 42px;
  line-height: 40px;
  animation-name: opacity;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}

.content__container__text {
  display: inline;
  float: left;
  margin: 0;
}

.content__container__list {
  margin-top: 0;
  padding-left: 110px;
  text-align: left;
  list-style: none;
  animation-name: change;
  animation-duration: 10s;
  animation-iteration-count: infinite;
}

.content__container__list__item {
  line-height:40px;
  margin:0;
}

@keyframes opacity {
  0%, 100% {opacity:0;}
  50% {opacity:1;}
}

@keyframes change {
  0%, 12.66%, 100% {transform:translate3d(0,0,0);}
  16.66%, 29.32% {transform:translate3d(0,-25%,0);}
  33.32%,45.98% {transform:translate3d(0,-50%,0);}
  49.98%,62.64% {transform:translate3d(0,-75%,0);}
  66.64%,79.3% {transform:translate3d(0,-50%,0);}
  83.3%,95.96% {transform:translate3d(0,-25%,0);}
}
</style>

### Языки

![Python](https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/c++%20-%2300599C.svg?&style=for-the-badge&logo=c%2B%2B&ogoColor=white)
![C#](https://img.shields.io/badge/c%23%20-%23239120.svg?&style=for-the-badge&logo=c-sharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

## 📫 Как со мной связаться:
Вы можете связаться со мной по электронной почте, указанной в моем профиле на github, или через любой из моих социальных аккаунтов.

[<img src="https://img.shields.io/badge/вконтакте-%232E87FB.svg?&style=for-the-badge&logo=vk&logoColor=white" height="40em" align="center" alt="Сылка на профиль ВК" title="Сылка на профиль ВК"/>](https://vk.com/honeynus)
