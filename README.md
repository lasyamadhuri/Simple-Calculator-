<!DOCTYPE html>
 <html lang="en">                                                                                                                                                   <head>
<title> JavaScript Calculator </title>
<style>
#clear{
    width: 270px;
    border: 3px solid rgb(127, 123, 123); 
    border-radius: 3px;
    padding: 20px;
    background-color: #554e4e; 
    color: white; 
}
.form {
    width: 300px;
    height: 580px;
    margin: auto;
    border: 3px solid rgb(186, 197, 210); 
    border-radius: 5px;
    padding: 25px;
}
input {
    width: 20px;
    background-color: #5f6063a0; 
    color: rgb(255, 253, 253);
    border: 2px solid rgb(132, 13, 13); 
    border-radius: 2px;
    padding: 28px;
    margin: 5px;
    font-size: 20px;
}
#calc{
    width: 250px;
    border: 5px solid black; 
    border-radius: 3px;
    padding: 20px;
    margin: auto;
}
</style>
</head>
<body>
    <div class="form">
<form name="form1">
    <!-- This input box shows the button pressed by the user in calculator. -->
  <input id="calc" type="text" name="answer"> <br> <br>
  <!-- Display the calculator button on the screen. -->
  <!-- onclick() function display the number pressed by the user. -->
  <input type="button" value="1" onclick="form1.answer.value += '1' ">
  <input type="button" value="2" onclick="form1.answer.value += '2' ">
  <input type="button" value="3" onclick="form1.answer.value += '3' ">
  <input type="button" value="+" onclick="form1.answer.value += '+' ">
  <br> <br>
  <input type="button" value="4" onclick="form1.answer.value += '4' ">
  <input type="button" value="5" onclick="form1.answer.value += '5' ">
  <input type="button" value="6" onclick="form1.answer.value += '6' ">
  <input type="button" value="-" onclick="form1.answer.value += '-' ">
  <br> <br>
  <input type="button" value="7" onclick="form1.answer.value += '7' ">
  <input type="button" value="8" onclick="form1.answer.value += '8' ">
  <input type="button" value="9" onclick="form1.answer.value += '9' ">
  <input type="button" value="" onclick="form1.answer.value += '' ">
  <br> <br>
  <input type="button" value="/" onclick="form1.answer.value += '/' ">
  <input type="button" value="0" onclick="form1.answer.value += '0' ">
  <input type="button" value="." onclick="form1.answer.value += '.' ">
  <!-- When we click on the '=' button, the onclick() shows the sum results on the calculator screen. -->
  <input type="button" value="=" onclick="form1.answer.value = eval(form1.answer.value) ">
  <br>
  <!-- Use cancel button to erase all data entered by the user. -->
  <input type="button" value="Clear All" onclick="form1.answer.value = '' " id="clear" >
  <br>
</form>
</div>
</body>
</html>
