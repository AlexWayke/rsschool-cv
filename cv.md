##Hello, my name is
#Poltavskiy Alexander


![Alexander Poltavskiy](./src/photo_2022-11-20_21-35-40.jpg)
====


##Contacts:
*Telegram: https://t.me/AlPoltavsky
*VK: https://vk.com/yuhcha
*Skype: live:.cid.f4d2227481fd3f6d


##A bit about self:
I live in Samara and working as a front-end developer for the "Guild PRO" company about 1.5 year.
I love board games and music, so I spend my free time to studies and hobbies.
I'm not a person of talented, but a lot of zeal.


##Here is a example of my code:
The function for finding "Tribonacci" numbers
```
function tribonacci(signature,n){
  let arr = signature;
  if(arr.length > n){
    arr = arr.slice(0,n);
  } else if(arr.length !== n) {
    let newInt = arr.slice(-3).reduce((acc,num)=> acc + num);
    arr.push(newInt);
    tribonacci(arr,n);
  }
  return arr
}
```


##And example of my personal projects:
[Pair game](https://github.com/AlexWayke/pair-game)
