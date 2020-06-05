# best-repo-ever
//Step 1
var pagebutton = document.getElementById('NextButton');
pagebutton.click();
setInterval(step2, 2000);
//Step 2
function step2(){
    var myname = document.getElementById('QR~QID2');
    myname.value = 'Avi Modi';
    var pagebutton = document.getElementById('NextButton');
    pagebutton.click();
    setInterval(step3, 2000);
}


//Step 3
function step3(){
    var myname = document.getElementById('QR~QID3');
    myname.value = 'Michael Brattman';
    var pagebutton = document.getElementById('NextButton');
    pagebutton.click();
    setInterval(step4, 2000);  
}

//Step 4
function step4(){
    document.getElementById('QR~QID4~7').checked = true;
    var pagebutton = document.getElementById('NextButton');
    pagebutton.click();
    setInterval(step5, 2000);
}

//Step 5
function step5() {
  document.getElementById('QR~QID5~2').checked = true;
  var pagebutton = document.getElementById('NextButton');
  pagebutton.click();  
}
