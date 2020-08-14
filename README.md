# Redux for Beginners Vanilla

Learning Vanilla-Redux and React-Redux

## Redux

-   상태 관리 라이브러리
-   컴포넌트들의 상태 관련 로직들을 다른 파일들로 분리시켜서 더욱 효율적으로 관리 할 수 있다.
-   컴포넌트끼리 상태를 공유하게 될 때 여러 컴포넌트를 거치지 않고도 손쉽게 상태 값을 전달 할 수 있다.
-   글로벌 상태 관리를 할 때 가장 효과적이다.

** ps. 유일한 솔루션은 아니며, Context API를 통해서도 동일한 작업을 할 수 있다. **

### Store

#### createStore

>

```
import { createStore } from "redux";
```
