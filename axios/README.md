# API-Pay-Truemoney-Gift-V100-Naelike

<img class="rounded" src="http://img.in.th/images/92f4aac2d777868b2a45c3454e48530b.png" width="220" alt="NaeLike"> 

> Truemoney Gift

@truemoney :+1: Web :  <https://www.truemoney.com/sendgift/> ..! :shipit:


# API GET URL

Service Line Notify Messages:
> ../pay-truemoney/gift[phone=paygift=]
- phone : เบรอ์ที่รับ อั๋งเปา
- paygift : ลิ้งอั๋งเปา


.JS : GET Service URL.
```
function getParameter(name, url = window.location.href) {
  name = name.replace(/[\[\]]/g, '\\$&');
  var regex = new RegExp('[?&]' + name + '(=([^&#]*)|&|#|$)'),
      results = regex.exec(url);
  if (!results) return null;
  if (!results[2]) return '';
  return decodeURIComponent(results[2].replace(/\+/g, ' '));
}
var phone = getParameter('phone');
var paygift = getParameter('paygift');
var getPhone = phone;
var gtePaygift = paygift;
var urlGet = '../pay-truemoney/gift' + '?phone=' + getPhone + '&paygift=' + gtePaygift
```
PHP : GET Service URL.
```
$get_phone = $_GET['phone'];
$gte_paygift = $_GET['paygift'];
$url_get = '../pay-truemoney/gift' . '?phone=' . $get_phone . '&paygift=' . $gte_paygift
```

# Axios GET Service Example 
```
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
```
```
function getParameter(name, url = window.location.href) {
  name = name.replace(/[\[\]]/g, '\\$&');
  var regex = new RegExp('[?&]' + name + '(=([^&#]*)|&|#|$)'),
      results = regex.exec(url);
  if (!results) return null;
  if (!results[2]) return '';
  return decodeURIComponent(results[2].replace(/\+/g, ' '));
}
var phone = getParameter('phone');
var paygift = getParameter('paygift');
var getPhone = phone;
var gtePaygift = paygift;
var urlGet = '../pay-truemoney/gift' + '?phone=' + getPhone + '&paygift=' + gtePaygift
```
```
axios({
  method: "get",
  url: urlGet,
})
.then(function(response) {
  console.log(response.data);
})
.catch(function(response) {
  console.log(response);
});
```

# Developer : NaeLike เนไลก์

<img class="rounded" src="http://img.in.th/images/c938fdabdf2a1d4b2deda8ffea4fa189.jpg" width="120" alt="NaeLike"> 

> Naelike เนไลก์

@เว็บไซต์ :+1: Web :  <https://naelike.com> ..! :shipit:
<br>
@ติดตาม :+1: Web :  <https://naelike.com/addmee> ..! :shipit:

TikTok :  <https://www.tiktok.com/@naelike6564>
<br>
Facebook :  <https://web.facebook.com/NaeLikePage>
<br>
Instagram :  <https://www.instagram.com/naelike_ig>
<br>


<a href="https://link.ckpzmc.xyz/dispnae"> 
   <img class="rounded" src="https://i.pinimg.com/originals/1a/9a/f1/1a9af177bdcd0bd93568e59bb7600cbe.png" width="120" alt="NaeLike"> 
   </br>
   <b class="fs-12">Discord คลิก..!</b> 
</a>
