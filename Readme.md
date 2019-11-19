## Task 1.2
```
var i = 0
for (i;; i++) {
   var cash = i*100
   if (cash >= 660) break;
}
console.log(i);
console.log(cash);
```

## Task 2.2
```
var name, pass;
var x = 3;
var y = 6;

function login() {
  name = prompt(" Enter your name: only letters and at least " + x + "characters ");
  if (name.length >= x && typeof name === "string" && typeof name !== 'undefined' && name !== null) {
    alert("Success"),
      pass = prompt(" Enter your password: at least " + y + "characters ");
    if (pass.length >= y && typeof pass !== 'undefined' && name !== null) {
      alert("Success");
    } else alert(" Please enter at least " + y + "characters "),
      login()
  } else alert(" Please enter only letters and at least " + x + "characters "),
    login()
}

login()
```
