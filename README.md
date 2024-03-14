Here are my solutions 

## 1. Here is the hoisted link and code where i have designed the UI using only HTML and CSS  
link:  
code:  

## 2. here is the code for 2nd problem  
   function getUrlParameterValue(url, parameter) {  
  var query = url.split("?")[1];  
  var params = query.split("&");  
  for (var i = 0; i < params.length; i++) {  
    var search = params[i].split("=");  
    if (search[0] === parameter) {  
      return search[1];  
    }  
  }  
  return null;  
}  

var url =  
  "https://www.kommunicate.io/poweredby?utm_source=https://www.kommunicate.io/&utm_medium=webplugin&utm_campaign=poweredby";  
  
console.log(getUrlParameterValue(url, "utm_medium"));  
console.log(getUrlParameterValue(url, "utm_campaign"));  


## 3. Here is the code for 3rd problem  
   function reverseNumber(number) {  
  var reversed = 0;  
  while (number !== 0) {  
    var digit = number % 10;  
    reversed = reversed * 10 + digit;  
    number = (number - digit) / 10;  
  }  
  
  return reversed;  
}  

var number = 149;  
console.log(reverseNumber(number));  


## 4.My best project

