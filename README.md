# minesweeper

cli용 지뢰찾기를 완성하시오.

### 다음의 함수의 내용을 채우시오

#### showMap

현재 지뢰판을 보여주는 함수. console.log(str)부분을 제거하고 지뢰찾기 로직에 맞게 잘 동작 시켜야 함.

#### gameOver

지뢰를 선택했을 시 실행되는 함수. 지뢰판의 열린 상태를 보여주고, "게임을 재시작하겠습니까?" 메시지를 띄움. Y를 입력 시 기 입력된 width, height, cntOfMine을 이용해 맵을 재생성하고 게임을 다시 시작.

#### revealMine

해당 블럭에 지뢰가 없을 때 동작하는 함수. 이웃한 8방면에 모두 지뢰가 없을 시, 8방면 모두에 revealMine을 호출해야 함.

#### isWin

승리를 판별하는 함수. 지뢰가 없는 모든 block이 covered된 경우에 true를 리턴

#### gameWin
게임 승리 시 실행되는 함 수. gameOver와 마찬가지로 지뢰판의 열린 상태를 보여주고, "게임을 재시작하겠습니까?" 메시지를 띄움. Y를 입력 시 기 입력된 width, height, cntOfMine을 이용해 맵을 재생성하고 게임을 다시 시작.

해당 함수를 모두 작성해 27일 자정까지 mongmaker721@gmail.com으로 제출. 29일까지 제출 가능하며, 하루 늦춰질 때마다 10%씩 감점.

기능 명세 및 체점 세부사항은 https://github.com/snuwebprogramming-21-1/hw1 와 유사하니 이를 참조.
