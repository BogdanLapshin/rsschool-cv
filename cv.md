# Bogdan Lapshin


## Contacts:
 - #### Phone Number:
    - +380687913760
 - #### Mail:
    - <bogdanizizmaila@gmail.com>
 - #### Telegram:
    - [Telegram](https://t.me/benzbogd)

## About me:
 - Beginner Front-end developer. I really like the business I am doing. My goal is to find a job in a good company as a web developer. Have experience with OpenCart. I quickly find contact with different people. Hardworking, determined and persistent. I take a creative approach to the task at hand.


## Skills:
 - HTML;
 - CSS;
 - Native JS
 - Bootstrap
 - Photoshop, Figma, Avocode

## Code:
    function getDataFromDB(id, callbackHandler) {
      function getRequestObject() {
          if (window.XMLHttpRequest) return new XMLHttpRequest();
          else if (window.ActiveXObject) return new ActiveXObject("Microsoft.XMLHTTP");
          window.alert("Ajax is not supported!");
          return null;
      }
      const request = getRequestObject();

      request.onreadystatechange = () => {
          if (request.readyState == 4 && request.status == 200) {
              result = JSON.parse(request.responseText);
              callbackHandler(result);
          }
      };
      request.open('GET', `${dbUrl}/${id}`, true);
      request.send(null);

    }
