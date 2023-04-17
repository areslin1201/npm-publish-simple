# 測試npm上傳文件

使用CRA、storybook、typescript創建按鈕組件

### 使用方式

#### 安裝
```shell
npm i ares-publish-npm-example
```

#### 引用
引用Map
```jsx
import { Map } from '@soulweblab/my-library';
import { TileLayer } from 'react-leaflet';

<Map width="100vw" bounds={[
  [42.5993718217880613, 1.5937492475355806],
  [45.9312500000000341, 7.6656250000000341]
]}>
  <TileLayer url="https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png"/>
</Map>
```