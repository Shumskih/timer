# Timer

'Timer' is a native javascript module for creating timer on a web page. It takes one parameter - date in format "2020-07-11".

Example of usage:

```javascript
timer('.timer', '2020-07-20');
```

Example of html markup:

```html
<div class="timer">
    <div class="timer__block">
        <span id="days">12</span>
        дней
    </div>
    <div class="timer__block">
        <span id="hours">20</span>
        часов
    </div>
    <div class="timer__block">
        <span id="minutes">56</span>
        минут
    </div>
    <div class="timer__block">
        <span id="seconds">20</span>
        секунд
    </div>
</div>
```
