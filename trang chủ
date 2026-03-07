<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nhóm 6</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>

:root {
    --primary-bg: #f0f4ff;
    --card-bg: rgba(255, 255, 255, 0.8);
    --accent-blue: #708ed6;
    --text-dark: #333;
    --shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
}

body {
    font-family: 'Segoe UI', sans-serif;
    background-color: var(--primary-bg);
    margin: 0;
    padding: 0;
}

/* ===== HEADER ===== */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
}

nav a {
    text-decoration: none;
    color: var(--text-dark);
    margin: 0 15px;
    font-weight: 500;
}

.auth-buttons button {
    padding: 8px 20px;
    border-radius: 20px;
    border: none;
    cursor: pointer;
    margin-left: 10px;
    font-weight: bold;
}

.btn-login { background: white; border: 1px solid #ddd; }
.btn-signup { background: var(--accent-blue); color: white; }

/* ===== SLIDER ===== */
.banner {
    position: relative;
    width: 90%;
    margin: 30px auto;
    overflow: hidden;
    border-radius: 20px;
    
}

.slides {
    display: flex;
    transition: transform 0.6s ease;
}

.slide {
    min-width: 100%;
}

.slide-img {
    width: 100%;
    height: auto;   /* QUAN TRỌNG */
    display: block;
}

    

/* ===== ARROWS ĐẸP HƠN ===== */
.prev, .next {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 55px;
    height: 55px;
    border-radius: 50%;
    border: none;
    background: rgba(255,255,255,0.9);
    color: #ff7a00;
    font-size: 22px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: 0.3s;
    box-shadow: 0 5px 20px rgba(0,0,0,0.2);
}

.prev:hover, .next:hover {
    background: #ff7a00;
    color: white;
    transform: translateY(-50%) scale(1.1);
}

.prev { left: 25px; }
.next { right: 25px; }
/* ===== CONTENT GRID ===== */
.container {
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
}

.grid-layout {
    display: grid;
    grid-template-columns: 1.5fr 1fr 1fr;
    gap: 20px;
}

.card {
    background: var(--card-bg);
    border-radius: 20px;
    padding: 20px;
    box-shadow: var(--shadow);
}

.member-item {
    background: #eef2ff;
    padding: 10px;
    border-radius: 12px;
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    text-decoration: none;
    color: inherit;
    transition: 0.3s;
}

.member-item:hover { background: #dce4ff; }

.info-card {
    display: flex;
    gap: 10px;
    padding: 10px;
    background: white;
    border-radius: 12px;
    margin-bottom: 10px;
}
/* ===== SECTION VĂN HỌC DÂN GIAN ===== */

.folk-section{
    width:100%;
    min-height:80vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:80px 20px;
}

.folk-section h1{
    font-size:45px;
    margin-bottom:20px;
}

.folk-section p{
    max-width:700px;
    font-size:18px;
    line-height:1.7;
}

.folk-img img{
    width:320px;
    margin-top:30px;
}

/* HIỆU ỨNG XUẤT HIỆN */
.reveal{
    opacity:0;
    transform: translateY(80px);
    transition: all 1s ease;
}

.reveal.active{
    opacity:1;
    transform: translateY(0);
}
/* HERO */

.hero{
    position:relative;
    height:500px;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    overflow:hidden;
}

/* nền hồng */

.hero-bg{
    position:absolute;
    width:85%;
    height:420px;
    background:linear-gradient(180deg,#f6b8b8,#f3a7a7);
    border-radius:60px 60px 200px 200px;
    top:40px;
    z-index:-1;
    box-shadow:0 20px 60px rgba(0,0,0,0.08);
}

/* chữ */

.hero-content h1{
    font-size:55px;
    margin-bottom:20px;
}

.hero-content p{
    font-size:18px;
    color:#444;
}

/* nút */

.btn-main{
    margin-top:20px;
    padding:12px 30px;
    border:none;
    border-radius:30px;
    background:#f39c12;
    color:white;
    font-size:16px;
    cursor:pointer;
}

.btn-main:hover{
    transform:scale(1.05);  
}
.book{
position:absolute;
width:120px;
animation:floatBook 5s ease-in-out infinite;
}

.book1{
left:80px;
top:140px;
}

.book2{
right:100px;
top:120px;
}

@keyframes floatBook{

0%{
transform:translateY(0px) rotate(-5deg);
}

50%{
transform:translateY(-25px) rotate(5deg);
}

100%{
transform:translateY(0px) rotate(-5deg);
}

}
.popup{
    display:none;
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.5);
    justify-content:center;
    align-items:center;
}

.popup-content{
    background:white;
    padding:30px;
    width:350px;
    border-radius:15px;
    text-align:center;
}

.popup-content input{
    width:100%;
    padding:10px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:8px;
}

.submit-btn{
    width:100%;
    padding:10px;
    background:#4CAF50;
    color:white;
    border:none;
    border-radius:8px;
    cursor:pointer;
}

.close{
    float:right;
    font-size:22px;
    cursor:pointer;
}
</style>

</head>

<body>

<header>
    <div><i class="fa-solid fa-circle-user fa-2xl"></i></div>

    <nav>
    <a href="nhom6.html">Trang chủ</a>
    <a href="tacpham.html">Tác phẩm</a>
    <a href="#">Tìm kiếm</a>
</nav>

    <div class="auth-buttons">
        <button class="btn-login" onclick="openLogin()">Đăng nhập</button>

<button class="btn-signup" onclick="openRegister()">Đăng ký</button>
    </div>
</header>

<!-- ===== SLIDER ===== -->
<div class="banner">
    <div class="slides">
        <div class="slide">
            <div>
    <img src="anh 1h.PNG" alt="hình nền" class="slide-img" >
    </div>
            
        </div>  

        <div class="slide">
            <div>
                <h1>Slide 2</h1>
                <p>Nội dung khác...</p>
            </div>
        </div>
    </div>

    <button class="prev">❮</button>
    <button class="next">❯</button>
</div>
<section class="hero reveal">

<div class="hero-bg"></div>

<div class="hero-content">

    <h1>VĂN HỌC DÂN GIAN NAM BỘ LÀ GÌ</h1>

    <p>
      Văn học dân gian Nam Bộ là tập hợp các sáng tác nghệ thuật  <br>
      ngôn từ truyền miệng (vè, truyện kể, ca dao) do người dân vùng đất phương Nam sáng tạo trong quá trình khai hoang, lao động và đấu tranh.
    </p>

    <button class="btn-main">Xem thêm →</button>

</div>

<!-- SÁCH BAY -->
<img src="sach 1.png" class="book book1">
<img src="sach 2.png" class="book book2">

</section>

<script>
const slides = document.querySelector('.slides');
const slide = document.querySelectorAll('.slide');
const nextBtn = document.querySelector('.next');
const prevBtn = document.querySelector('.prev');

let index = 0;
const totalSlides = slide.length;

function updateSlide() {
    slides.style.transform = `translateX(-${index * 100}%)`;
}

nextBtn.addEventListener('click', () => {
    index = (index + 1) % totalSlides;
    updateSlide();
});

prevBtn.addEventListener('click', () => {
    index = (index - 1 + totalSlides) % totalSlides;
    updateSlide();
});
</script>
<script>

function revealOnScroll(){
    const reveals = document.querySelectorAll(".reveal");

    for(let i = 0; i < reveals.length; i++){

        let windowHeight = window.innerHeight;
        let elementTop = reveals[i].getBoundingClientRect().top;
        let visible = 150;

        if(elementTop < windowHeight - visible){
            reveals[i].classList.add("active");
        }
    }
}

window.addEventListener("scroll", revealOnScroll);

</script>
<script>

function openLogin(){
    document.getElementById("loginForm").style.display="flex";
}

function openRegister(){
    document.getElementById("registerForm").style.display="flex";
}

function closeForm(id){
    document.getElementById(id).style.display="none";
}

function switchToRegister(){
    closeForm("loginForm");
    openRegister();
}

function switchToLogin(){
    closeForm("registerForm");
    openLogin();
}

</script>

</section>

<!-- FORM ĐĂNG NHẬP -->
<div id="loginForm" class="popup">
    <div class="popup-content">
        <span class="close" onclick="closeForm('loginForm')">&times;</span>

        <h2>Đăng nhập</h2>

        <input type="text" placeholder="Tên đăng nhập">
        <input type="password" placeholder="Mật khẩu">

        <button class="submit-btn">Đăng nhập</button>

        <p>Chưa có tài khoản?
        <a href="#" onclick="switchToRegister()">Đăng ký</a>
        </p>
    </div>
</div>

<!-- FORM ĐĂNG KÝ -->
<div id="registerForm" class="popup">
    <div class="popup-content">
        <span class="close" onclick="closeForm('registerForm')">&times;</span>

        <h2>Đăng ký</h2>

     <input type="text" id="regUser" placeholder="Tên đăng nhập">
<input type="email" id="regEmail" placeholder="Email">
<input type="password" id="regPass" placeholder="Mật khẩu">

        <button class="submit-btn" onclick="register()">Đăng ký</button>

        <p>Đã có tài khoản?
        <a href="#" onclick="switchToLogin()">Đăng nhập</a>
        </p>
    </div>
</div>
<script>

function register() {

let username = document.getElementById("regUser").value;
let email = document.getElementById("regEmail").value;
let password = document.getElementById("regPass").value;

if(username === "" || email === "" || password === ""){
alert("Vui lòng nhập đầy đủ thông tin!");
return;
}

localStorage.setItem("username", username);
localStorage.setItem("password", password);

alert("Đăng ký thành công!");

closeForm('registerForm');

}

</script>
</body>
</html>
