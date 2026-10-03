# <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LUNA — Clothing Store</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:Arial, sans-serif;
  background:#f7f5f0;
  color:#171717;
}

header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:22px 6%;
  background:white;
  position:sticky;
  top:0;
  z-index:10;
  border-bottom:1px solid #eee;
}

.logo{
  font-size:28px;
  font-weight:800;
  letter-spacing:5px;
}

nav a{
  margin:0 15px;
  text-decoration:none;
  color:#222;
}

button{
  cursor:pointer;
  border:0;
}

.cart{
  background:#171717;
  color:white;
  padding:12px 18px;
  border-radius:4px;
}

.hero{
  min-height:520px;
  display:flex;
  align-items:center;
  padding:70px 7%;
  background:linear-gradient(120deg,#ded8cd,#aaa196);
}

.hero-content{
  max-width:600px;
}

.hero h1{
  font-size:64px;
  line-height:1;
  margin:15px 0;
}

.hero p{
  font-size:18px;
  color:#444;
  margin-bottom:25px;
}

.shop-btn{
  background:#171717;
  color:white;
  padding:15px 28px;
  border-radius:4px;
}

section{
  padding:70px 7%;
}

.section-title{
  font-size:36px;
  margin-bottom:35px;
}

.categories{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
}

.category{
  height:260px;
  padding:25px;
  display:flex;
  align-items:end;
  color:white;
  font-size:25px;
  font-weight:bold;
  background-size:cover;
  background-position:center;
  border-radius:5px;
}

.everyday{
  background:linear-gradient(135deg,#bdb4a8,#716960);
}

.outerwear{
  background:linear-gradient(135deg,#414447,#171819);
}

.essentials{
  background:linear-gradient(135deg,#eee9df,#aaa39a);
  color:#171717;
}

.products{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:20px;
}

.product{
  background:white;
  padding-bottom:20px;
  border-radius:5px;
  overflow:hidden;
}

.product-img{
  height:300px;
  display:flex;
  align-items:center;
  justify-content:center;
  background:#ddd;
  font-size:70px;
}

.black{
  background:#171717;
  color:white;
}

.beige{
  background:#d7c9b8;
}

.brown{
  background:#795d4b;
  color:white;
}

.product-info{
  padding:18px;
}

.product-info h3{
  margin-bottom:7px;
}

.price{
  font-weight:bold;
  margin:12px 0;
}

.add{
  width:100%;
  padding:12px;
  background:#171717;
  color:white;
  border-radius:3px;
}

.banner{
  text-align:center;
  background:#171717;
  color:white;
  padding:65px 20px;
}

.banner h2{
  font-size:42px;
  margin-bottom:10px;
}

footer{
  padding:40px 7%;
  background:white;
  display:flex;
  justify-content:space-between;
}

.overlay{
  display:none;
  position:fixed;
  inset:0;
  background:rgba(0,0,0,.45);
  z-index:20;
}

.panel{
  position:absolute;
  right:0;
  top:0;
  height:100%;
  width:390px;
  max-width:100%;
  background:white;
  padding:30px;
  overflow:auto;
}

.close{
  float:right;
  font-size:25px;
  background:none;
}

input,select,textarea{
  width:100%;
  padding:
