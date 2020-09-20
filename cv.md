# Yaugheni Tsimakhovich

  Student
  
## Contact

  * e-mail: 7301827@protonmail;
  * phone: +375(44)7301827
  * Telegram: @tievan__
  
## Summary

  *I want to become a front-end develover. 
  I graduated from the Academy of MIA in 2014. 
  Currently working as a jurist
  My strengths are stress resistance, the desire to learn something new, I learn quickly and am attentive to the little things in my work.*
  
## Skills 

  * HTML
  * CSS
  * JS
  
## Code example
```
        function transform(arr) {
        if (!Array.isArray(arr)) {
          throw new Error();
      }
        let newArr = [];
        for (let i = 0; i < arr.length; i++) {
         if(arr[i] === '--discard-next') {
           if (arr.length - i >= 2) {
            i++
           }
         } else if(arr[i] === '--discard-prev') {
            if (i >= 1 && arr[i - 2] !== "--discard-next") {
              newArr.pop()
            }
         }else if(arr[i] === "--double-next") {
           if(arr.length - i >= 2) {
             newArr.push(arr[i+1])
           }
         }else if(arr[i] === "--double-prev") {
           if(i >= 1 && arr[i-2] !== "--discard-next") {
             newArr.push(arr[i-1])
           }
         } else {
          newArr.push(arr[i])
        }
        }
        return newArr
      };

```
## Education

  * *Academy of MIA  (2014 specialist)*
  * *Belorussian State Economic University (student)*
  
  
## English

  English (B1)
