# ude-clone
*, html {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
​
img {
  width: 100%;
}
​
​
.mainWrapper {
  height: 100vh;
  display: flex;
}
​
.navbar {
  width: 15%;
  height: 100vh;
}
​
.mainArea {
  width: 70%;
}
​
.storiesWrapper {
  width: 20%;
  padding: 1rem 1rem 0 0;
}
​
.userCard {
  display: flex;
  align-items: center;
  margin-top: 1rem;
}
​
.imgWrapper img {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  object-fit: cover;
}
​
.imgWrapper {
  padding: 5px;
  background-image: url('../img/instbg.png');
  background-size: cover;
  background-position: center;
}
​
.userDetails {
  margin-left: 0.6rem;
}
​
.userDetails .username {
  font-size: 1rem;
  font-weight: 800;
}
.userDetails .userHandle {
  font-size: 0.8rem;
  font-weight: 800;
  color: #545454;
}
​
​
@media screen and (max-width: 800px) {
  .storiesWrapper {
    display: none;
  }
​
  .navbar {
    display: none;
  }
}
https://res.cloudinary.com/dfqwimmnp/image/upload/v1669685994/IMG_9244_ru4cxp.jpg