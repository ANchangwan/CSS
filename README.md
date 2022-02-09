# position

## position: fixed
- element가 처음 생성된 자리에 고정.

## position: relative
- element가 '처음 생성된 위치'를 기준점으로, top bottom left right으로 위치를 조금씩 수정할 수 있다.

## position: absolute
- 가장 가까운 relative 부모를 기준으로 이동 position:relative; 를 해주면 부모가 된다. 없으면 body.

# Transitions
transitions은 상태가 바뀌는 요소가 있을 때 사용한다.</br>
ex) hover, active, focus
- linear: 일정하게 변함
- ease-in: 시작과 끝이 느림
- ease-in-out: 시작이 빠르고 끝이 느림

all : 변화요소를 한번에 다룬다
- 따로 다루고 싶으면 속성을 지정하면 된다.
ex) transition: background-color 5s linear, color 1s ease-in;
