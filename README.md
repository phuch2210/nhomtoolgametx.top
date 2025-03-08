.container{
    width: 300px;
    border: 2px solid rgb(78, 238, 112);
    border-radius: 10px;
    text-align: center;
    backdrop-filter: blur(5px);
    background: transparent;
    padding: 20px;
    font-size: 18px;
    text-align: center;
    border: 5px solid red; /* Border ban đầu */
    animation: blink-border 1s infinite; /* Áp dụng animation */
      }
      
      /* Keyframes cho hiệu ứng nhấp nháy */
      @keyframes blink-border {
        0% {
          border-color: rgb(255, 0, 0); /* Màu ban đầu */
        }
        50% {
          border-color: transparent; /* Khi nhấp nháy border sẽ biến mất */
        }
        100% {
          border-color: red; /* Trở lại màu ban đầu */
        }
}
.circle-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 30px;
}
.circle {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    margin: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    font-size: 18px;
    font-weight: bold;
    color: white;
    transition: opacity 0.3s ease;
}
.circle1 {
    background-color: rgb(255, 59, 59);
    color: black;
    border: 2px solid white;
    font-family: sans-serif;
    font-style: italic;
}
.circle2 {
    background-color: rgb(30, 255, 0);
    color: black;
    border: 2px solid white;
    font-family: sans-serif;
    font-style: italic;
}
button{
    width: 160PX;
    height: 30px;
    border: none;
    border-radius: 30px;
    margin-top: 15px;
    background: rgb(230, 48, 48);
}
body{
    display: flex;
    justify-content: center;
    margin-top: 200px;
    background-image: url('./backgroud.jfif');
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
    background-size: cover;
}
input{
    height: 30px;
    border-radius: 30px;
}
.error {
  color: red;
  margin-top: 10px;
  font-family: sans-serif;
  font-style: italic;
  font-weight: bold;
}
.counter{
  color: white;
  font-family: sans-serif;
  font-style: italic;
}
.percent-display{
  color: white;
  border: 2px solid;
  width: 100%;
  height: 30px;
  border-radius: 30px;
  background: rgb(255, 139, 139);
  margin-top: 10px;
  font-family: sans-serif;
  font-style: italic;
  font-weight: bold;
}
.baytamclub{
  width: 100px;
  border-radius: 30px;
}
