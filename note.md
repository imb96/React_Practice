모듈 CSS 사용법
CSS 파일명: XXX.module.css
import classes from 'XXX.module.css'
className={}

```jsx
import classes from "./Card.module.css";
const Card = (props) => {
  return <div className={classes.card}>{props.children}</div>;
};
```

```css
.card {
  background-color: white;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  border-radius: 10px;
}
```

useState vs useRef ?
값만 읽고 싶다면 ref가 더 나은 것 같다.
state를 사용하면 깔끔하지만 코드가 좀더 길고 ref를 사용하면 편하게 요소에 접근할 수 있고 코드가 줄어들지만 dom을 조작해야한다
