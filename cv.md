# Volkov Danil
### Frontend Developer
***
### Contact information:
**Phone:** +7 (912) 0517244

**E-mail:** 79120517244@yandex.ru

**Telegram:** @Snake911

[**Linkedin**](https://www.linkedin.com/in/volkovdanil/)

## About me
***
Since 2018 I have been working as a web developer. I made up and integrated the layout for Bitrix. React and related tools are interesting. I aim to develop in this direction.

## Skills
***
* HTML5
* CSS3
* SASS (Basic)
* JavaScript
* PHP
* Git
* React (Basic)

## Code example
***
#### RGB To Hex Conversion
The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value.

```
function rgb(...color){
  return color.reduce((hex, item) => {
    if(item < 0){
      item = 0;
    } else if (item > 255){
      item = 255;
    }
    var colorHEX = item.toString(16).toUpperCase();
    if(colorHEX.length == 1) {
      colorHEX = '0' + colorHEX;
    }
    return hex + colorHEX;
  }, '');
};
```
## Courses
***

* Stepik - [Basic HTML & CSS](https://stepik.org/cert/106210)
* Stepik - [JavaScript for beginners](https://stepik.org/cert/98515)
* JavaScript Manual on learn.javascript.ru (in progress)

## Languages
***
* English - A2 (in progress)
* Russian - Native