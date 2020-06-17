# CSS position 속성 정리

#### 1. static

모든 태그의 기본 속성. 좌에서 우로, 위에서 아래로 배치된다

#### 2. relative

static 기준으로 top, left, right, bottom 속성을 이용해 위치를 변경할 수 있다. 

#### 3. absolute

**static 속성을 가지고 있지 않은** 부모를 기준으로 움직인다. 부모 중에 position이 relative, absolute, fixed인 태그가 없다면 가장 위의 body 태그가 기준이 된다.

#### 4. fixed

브라우저 창을 기준으로 고정된 위치에서 움직인다.