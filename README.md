# Project Build a Telephone Number Validator 🚀

## Project Description 📝

I create this project becuase of learning and this was fantastic project it check the us number that is valid or invaid number
I learn a lot things in this project special take a input from user and show the result in text by using button check an also we can clear the input of user.the simple design that i use it it make my project stand out 

```html
<div class="phone-container">
    <div class="phone-background">
        <div class="phone-camera"></div>
    </div>
    <label for="user-input">Enter a Phone Number:</label>
    <input maxlength="20" type="text" id="user-input" value="" />
    <div id="results-div"></div>
    <div class="phone-footer">
        <button class="btn-styles" id="check-btn">Check</button>
        <button class="btn-styles" id="clear-btn">Clear</button>
    </div>
</div>
```

```css
#results-div {
  overflow-y: auto;
  height: 265px;
  width: 100%;
}

.results-text {
  font-size: 1.2rem;
  padding: 5px;
  text-align: var(--center-text);
  margin: 10px 0;
}
```

```Java Script
function checkValidNumber(input) {
  const countryCode = '^(1\\s?)?';
  const areaCode = '(\\([0-9]{3}\\)|[0-9]{3})';
  const spacesDashes = '[\\s\\-]?';
  const phoneNumber = '[0-9]{3}[\\s\\-]?[0-9]{4}$';
  const phoneRegex = new RegExp(`${countryCode}${areaCode}${spacesDashes}${phoneNumber}`);
  resultsDiv.innerHTML = `${phoneRegex.test(input) ? 'Valid' : 'Invalid'} US number: ${input}`;
}
```

## Demo 📸
life demo link [https://humuyar.github.io/Build_a_telephone_number_validator/]

## Technologies Used 🛠️
- HTML
- CSS
- JAVA SCRIPT

## Installation 💻

```clone
  git@github.com:humuyar/Build_a_telephone_number_validator.git
```
## Features ⭐
- This website is a responsive website for Telephone number validator checker. 

## Author 👩‍💼
Humaira ✨Qabooli✨
- Github: https://github.com/humuyar/Build_a_telephone_number_validator/pull/1✔
- LinkedIn: [www.linked in/Humaira (Hmui) Qabooli.com](https://www.linkedin.com/in/humaira-qabooli-0aa529309/)✔
- Email: humiq6071@gmail.com✔

## Contributing 🤝
🎇 by using this link you can share your opinion : https://github.com/humuyar/Build_a_telephone_number_validator/issues