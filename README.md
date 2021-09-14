<!DOCTYPE HTML>
<html>
<head><title>Hai muhammad kaamil</title>
<!-- Created By your cuteee girlf hihi -->
<script>alert ('hai')
alert ('ini sebagai bentuk maaf aku')</script>
<script language="JavaScript"> 
 
function tb5_makeArray(n){
 this.length = n;
 return this.length;
}
 
tb5_messages = new tb5_makeArray(7);
tb5_messages[0] = "Haloooo sayang akuuuu";
tb5_messages[1] = "Aku Mau Kamu Tau";
tb5_messages[2] = "Aku Sayang banget tau Sama Kamu";
tb5_messages[3] = "hihiiii maaaf yaaa kalo sukaa bikin kesel kamuuu";
tb5_messages[4] = "taapiiii, aku pengen kamu tauuu if i love u sooo muchhhh until i dont know sampe kapan";
tb5_messages[5] = "jangann nyerah sama aku yaa gantengg, nantiii aku sedih gaada kamu";
tb5_messages[6] = "i hope u can accept me whatever who i am";
tb5_messages[7] = "makasih yaa ganteng udahh sayang sma aku";
tb5_messages[8] = "pleaseeee bertahan lebih jauh yukkk samaa akuuuu";
tb5_messages[9] = "I WUV U SO MATCHAAAAAAA!♡";
tb5_rptType = 'infinite';
tb5_rptNbr = 20;
tb5_speed = 30;
tb5_delay = 2000;
var tb5_counter=2;
var tb5_currMsg=0;
var tb5_stsmsg="";
function tb5_shuffle(arr){
var k;
for (i=0; i<arr.length; i++){
 k = Math.round(Math.random() * (arr.length - i - 1)) + i;
 temp = arr[i];arr[i]=arr[k];arr[k]=temp;
}
return arr;
