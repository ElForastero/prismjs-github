# prismjs-github
prism.js color scheme close to GitHub colors

<img src="Screen Shot 2019-04-19 at 12.33.08 AM.png" />


```jsx
import React from 'react';
import classNames from 'classnames/bind';
import styles from './Container.module.css';

const cx = classNames.bind(styles);

const Container = ({ children }) => (
  <div className={cx('container')}>{children}</div>
);

export default Container;
```
