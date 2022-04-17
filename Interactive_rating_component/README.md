## 새로 배운것

### css
 - constant var css
    ```css
    :root {
        --mobile-width: 375px;
        --desctop-width: 1440px;

        --very-dark-blue: hsl(216, 12%, 8%);
        --dark-blue: hsl(213, 19%, 18%);
        --medium-grey: hsl(216, 12%, 40%);
        --light-gray: hsl(217, 12%, 63%);
        --white: hsl(0, 0%, 100%);
        --primary: hsl(25, 97%, 53%);

        --font-size: 15px;

        --font-family: Overpass;
        --font-weight-small: 400;
        --font-weight-big: 700;
      }
   ```

   - css를 변수로 저장하여 재사용할 수 있음을 알았다.
 - css 분리(interface 분리 원칙과 비슷)
   - css의 기능을 잘게 쪼개서 재사용 할 수 있다.
   - ex) hidden, flex-center,hoverable 등
 - :before 을 이용하여 content를 직접 삽입할 수 있다.
 - input style을 label과 함께 이용하여 커스텀 할 수 있다.
 ``` css
 input[type='radio'] {
        display: none;
      }

input[type='radio']:checked + label {
  color: var(--white);
  background-color: var(--light-gray);
}
 ```

### html
- fieldset을 이용하여 radio input을 관리할 수 있다.
- img tag를 감쌀때 figure 태그를 container로 이용할 수 있다.

### js
- formData객체를 이용하여 form객체의 데이터를 쉽게 뽑아낼 수 있다.
