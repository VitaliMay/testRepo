# Vitali Majewski
### Junior Front-End Developer (Entry Level)

----

### Contact information:
:phone: **Phone:** +375 29 6-906-306  
:envelope: **E-mail:** mvt30@mail.ru  
:octocat: **GitHub:** [VitaliMay](https://github.com/VitaliMay)

----

### About Me :dog:
I am an excellent team worker  


----
### Skills  :chart_with_upwards_trend:
* HTML (in progress) <br>
* CSS (in progress)  <br>
* JavaScript (in progress) <br>
* Git, GitHub (in progress) <br>

----
### Code example:

[**Bingo Card KATA from CODEWARS**](https://www.codewars.com/kata/bingo-card)<br>
[![logo](/assets/svg/codewars_button_icon_151901.png)](https://www.codewars.com/kata/bingo-card)<br>

*And my first recursion :)*<br>

```javascript

function getCard() {
  let BINGO = []
  for (let i = 0; i < 5; i++){
    BINGO[i] = 'B' + (Math.floor(Math.random() * (15)) + 1)
    BINGO[i+5] = 'I' + (Math.floor(Math.random() * (15)) + 16)
    BINGO[i+5+4] = 'N' + (Math.floor(Math.random() * (15)) + 31)
    BINGO[i+5+4+5] = 'G' + (Math.floor(Math.random() * (15)) + 46)
    BINGO[i+5+4+5+5] = 'O' + (Math.floor(Math.random() * (15)) + 61)
  }
  if (BINGO.length === [...new Set(BINGO)].length) return BINGO;
  return getCard()
}

```

-----
### Languages:
* :us: English - (A2) Pre-Intermediate
* :ru: Russian - Native
* :poland: Polish - Basic
* :ukraine: Ukrainian - Basic

-----
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
