# learn-scss
* Viet CSS long nhau

* Dinh nghia bien

* import file _header.scss => @import './_header'

* tao function vs mixin 
```javascript

 @mixin flexCenter($direction, $bg) {
     display: flex;
     justify-content: center;
     align-items: center;
     height: 100vh;
     flex-direction: $direction;
     background-color: $bg;
 }
=> USE:  @include flexCenter(column,$primaryBtn)


```

* extend css => override

* ::after => Duoc su dung de them noi dung vao 1 phan tu co thuoc tinh noi dung
