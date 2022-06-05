<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
.row {
  display: flex;
  flex-wrap: wrap;
}

.column {
  flex: 25%;
  padding: 0em;
  border:.2em solid #000000;
  background-color:#ccc;
  
}
.relative {
  position: relative;
  width: 6em;
  border: 3px solid #2173ad;
  padding-right: .5em;
  padding-left: .5em;
  padding-top: 0em;
  justify-content: center;
}
.p{
  padding: 1em;
  padding-top: 0em;
}
#chicken{
  color: #010101;
 background-color:  #f698e0;
}
#beef{
  color: #ffffff;
 background-color:  #ff0000;
}

#sushi{
  color: #000000;
  background-color:  #e5ff00;
}
@media screen and (min-width:992px){
 .relative{
   left: 63%;
 }
 .column{
    margin: 2%;
  }
}
@media screen and (min-width:767px) and (max-width:991px){
  .column{
    margin: 5%;
  }
  .relative{
   left: 65%;
 }
 #sushi{
   left: 84%;
 }
}
@media screen and (max-width:766px) {
.column{
  margin-bottom:5em;
  margin: 2em;
}
.relative{
   left: 55%;
 }
}

</style>

</head>
<body>

<h2>Our Menu</h2>
<p><strong>Platillos.</strong> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ear.</br></p>

<div class="row">
  <div class="column">
    <div class="relative"id="chicken"><p>Chicken</p></div>
    <p class="p">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea </p>
  </div>
  
  <div class="column">
    <div class="relative" id="beef"><p>Beef</p></div>
    <p class="p">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea </p>
  </div>
  
  <div class="column">
    <div class="relative" id="sushi"><p>Sushi</p></div>
    <p class="p">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea </p>
  </div>
  
</div>

</body>
</html>
