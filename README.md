# is-printable-keycode
Detect if keycode is a width affecting character (including spaces and deletion)

```javascript
npm install is-printable-keycode
```

```javascript
import isPrintableKeycode from 'is-printable-keycode';

input.addEventListener('keydown', (e) => {
    if (isPrintableKeycode(e.keyCode)) {
        // do something
    }
}, false);
```
