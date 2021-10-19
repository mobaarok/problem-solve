# Problem List

### Problem 1-
A input is given, example- "javascriptloops";
Now First, print each vowel in  on a new line. The English vowels are a, e, i, o, and u, and each vowel must be printed in the same order as it appeared in .

Second, print each consonant (i.e., non-vowel) in  on a new line in the same order as it appeared in .
```js
//code will be like that
function vowelsAndConsonants(s) {
    
     for(var i = 0; i < s.length; i++) {
         if(s[i] == 'a' || s[i] == 'e' || s[i] == 'i' || s[i] == 'o' || s[i] == 'u') {
            console.log(s[i]);    
         } 
     }
     for(var i = 0; i < s.length; i++) {
         if(!(s[i] == 'a' || s[i] == 'e' || s[i] == 'i' || s[i] == 'o' || s[i] == 'u')) {
            console.log(s[i]);    
         } 
     }
}

vowelsAndConsonants('javascriptloops')
```
** Output will be...**
```js
a
a
i
o
o
j
v
s
c
r
p
t
l
p
s
```