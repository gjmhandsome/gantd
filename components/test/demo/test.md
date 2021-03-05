---
order: 0
title: 测试
---

测试2


```jsx
import { BasicTest } from 'antd-gjm';
console.log('BasicTest', BasicTest)
const TestExample: React.FC = () => { 
  return (
    <div>
      <BasicTest />
    </div>
  );
}

ReactDOM.render(
  <div>
    <TestExample />
  </div>,
  mountNode,
);
```
