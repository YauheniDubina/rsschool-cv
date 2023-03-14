![avatar](/assets/avatar.png)
## **Yauheni Dubina**
### Brest/Belarus

## Contacts:
- **Phone number :** +375255264042
- **Email :** yauheni.dubina@gmail.com
- **GitHub :** [YauheniDubina](https://github.com/YauheniDubina)
- **Social networks:**  
  [![telegram](/assets/telegram.png)](http://t.me/eug_nik)[![linkedin](/assets/link.png)](https://www.linkedin.com/in/yauheni-dubina-9ab983129/)[![Facebook](/assets/facebook.png)](https://www.facebook.com/profile.php?id=100023899583235)

## About me:
<p>Hi,My name is Yauheni and i am a beginner Frontend developer.I've been developing landing pages and single-page application for my own purposes.I don't have experience in commercial development, but, currently, i am iproving my web development skils to find a job.My goal is get a job offer and start my professional developer cereer in the near future. </p>

## Education:
* Brest State Technical University 2013-2017
    * Faculty of Electronic Information Systems
	    * Software engineer

## Experience:
* online courses
* reading documentation
* making pet project
## Skills:
* HTML 5
* CSS
    * preprocessor SASS
* JavaScript
* CMS
    * Wordpress
    * Joomla
* Photoshop,Avocode,Marsy
* Skills of working with primary documentation
* English / Pre-intermediate(A2)

## Code examples:
<p>Some functions from TICTACTOE application (JS):</p>

```javascript
const play = (element, index) => {
  let winner;
  element.innerHTML = currentPlayer;
  element.disabled = true;
  currentMove[index] = currentPlayer;
  currentPlayer = currentPlayer == `X` ? `O` : `X`;
  currentTurn.innerHTML = `Player ${currentPlayer} turn`;
  step++;
  for (let i = 0; i < winCombinations.length; i++) {
    let condition = winCombinations[i];

    let a = currentMove[condition[0]];
    let b = currentMove[condition[1]];
    let c = currentMove[condition[2]];
    if (a == "" || b == "" || c == "") {
      continue;
    }
    if (a == b && a == c) {
      a == `X`
        ? (result.innerHTML = Number(++result[0].innerHTML))
        : (result.innerHTML = Number(++result[2].innerHTML));
      currentTurn.innerHTML = `Player ${a} won`;
      alert(`Player ${a} won`);
      cells.forEach((btn) => (btn.disabled = true));
      winner = a;
      break;
    }
  }

  if (step == 9 && !winner) {
    result.innerHTML = Number(++result[1].innerHTML);
    currentTurn.innerHTML = `DRAW`;
    alert(`Draw`);
  }
  return;
};
```
## English:
Pre-intermediate(A2)-I am improving my English skills with online courses.