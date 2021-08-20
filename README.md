# angular-forin

app.component.ts

```js
import { Component, VERSION } from '@angular/core';

@Component({
  selector: 'my-app',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
  constructor() {
    let employees = ['Akshay Patel', 'Panth Patel'];
    for (let employee in employees) {
      console.log(employee);
    }
  }
}
```


![image](https://user-images.githubusercontent.com/38757471/130256568-d6c3fcf4-c507-488c-b9e4-88abcd5f4f9e.png)
