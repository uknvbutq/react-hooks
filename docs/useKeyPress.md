
# `useKeyPress`

Detect keydown and keyup events for some keyboard letter when is pressed.

## Usage
```jsx
import { usekeyPress } from "hook/location";

const App = () => {

    const ninjaIsPressed = useKeyPress("n");

    return (
        <div>
            { ninjaIsPressed && "🐱‍👤" }
        </div>
    )
}
```

## API

```js
const isPressed = useKeyPress(letter);
```

- **isPressed**: *boolean* - state when the letter key is pressed
- **letter**: *string* - the letter