# Maksim Astapenok
***
## Contacts:
***
* **Phone:** +375 33 35-90-475
* **E-mail:** maxim.ast.1998@gmail.com
* **Telegram:** @one_new_man
## About Me:
***
I studied at technical university, worked by teacher but
I **WANNA** be a frontend developer and I **WILL!!**
## Skills:
***
* HTML5, CSS3
* Javascript
* Git, GitHub
## Code Example:
***
**Highest Scoring Word KATA from CodeWars:** _Given a string of words, you need to find the highest scoring word.
Each letter of a word scores points according to its position in the alphabet: a = 1, b = 2, c = 3 etc.
You need to return the highest scoring word as a string.
If two words score the same, return the word that appears earliest in the original string.
All letters will be lowercase and all inputs will be valid._
```
function high(str){
  return str.split(' ').reduce((max, current) => {
    return current.split('').reduce((pv, cv) => {
      return pv += cv.charCodeAt(0) - 96
    },0) > max.split('').reduce((pv, cv) => {
      return pv += cv.charCodeAt(0) - 96
    },0)? max = current: max
  },'a')
}
```


## Experience:
***
* RS Schools Course «JavaScript/Front-end 2022Q3. Stage 1» (in progress)
## Education:
***
* University: Belarusian National Technical University

## Languages:
***
* English - A2
* Russian - Native
