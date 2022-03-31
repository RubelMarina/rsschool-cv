# **Marina Rubel**
***
*Contact*  
email: marina88rubel@gmail.com  
phone: +375-29-713-93-58  
LinkedIn: linkedin.com/in/marina-rubel-a36191220 
***
*About Myself*  
I am an engeneer. I have been working at JSC "Naftan" since 2011. Our departnent is engaged in plainning of the rate of matirials, organizing and monitoring the implementation of production plans and many other activities. In 2019 I completed my master's degree in chemical technology. Today I am trying  to change the field of activity and study front-end development. At the initial stage, I graduated courses "SkillUP" with honors, now I am a student of rsschool. I am sure that I will definitely achieve success in this area.
***

*Skills*
* HTML, CSS, JS
* Angular
* Git
* gulp
* typescript
* bootstrap 
***
*Code*  
```
function createLinksFromDomains(str) {
  let arr = str.split(' ');
  let arr1 = arr.map(function (i) {
    let str = '';
    let str1 = i.match('^(http:|https:)\\/\\/(?!:\\/\\/)([a-zA-Z0-9-_]+\\.)*[a-zA-Z0-9][a-zA-Z0-9-_]+\\.[a-zA-Z]{2,5}$', 'gi');
    if (str1) {str = i.replace(i, `<a href="${i}" target="_blank">${i.replace(/^(http:|https:)\/\//gi, '')}</a>`)
    return str} else {
      return i;};
  });
  let result = arr1.join(' ');
  return result;
};
```
***
*Links to project*  
[слайдер](https://rubelmarina.github.io/js-native-slider/"click")  
[cinema](https://rubelmarina.github.io/cinema_rubel/"click")    
[grid](https://rubelmarina.github.io/grid__rubel/"click")    
***
*Education*   
"SkillUp" - frontend developer;  
"Polotsk State University" - master;  
***
*Languages*  
English - B1;  
Russian - native;  
***