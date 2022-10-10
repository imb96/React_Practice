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
