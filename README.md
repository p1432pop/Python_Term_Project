## Random Tower Defense
### Basic Information
* 21101237 Han Jeong Hyeon

### How To Play
* 게임의 목표는 타워를 설치해 몬스터가 목표 지점에 도달하기 전에 섬멸시키는 것입니다.
* 게임은 총 10 라운드로 진행되며 게임 실행 10초 후부터 몬스터가 등장합니다.
* 각 라운드마다 1초에 1마리씩 총 20마리의 몬스터가 등장하며 마지막 몬스터가 소환된 시점을 기준으로 20초 후 다음 라운드가 진행됩니다.
* 모든 몬스터는 왼쪽 상단에서 등장하며 길을 따라 오른쪽 하단에 있는 목표 지점으로 이동합니다.
* 게임 시작시 30개의 :heart:와 150 :coin:를 가지고 시작합니다.
  * 몬스터가 목표 지점에 도달하기 전까지 처치하지 못할 경우 1개의 :heart:가 소모되며 Final 라운드가 끝나기 전에 :heart:를 모두 소모할 경우 게임에서 패배합니다.
  * Gold는 타워를 설치하거나 판매할 때 사용되는 화폐이며 몬스터 처치시 5 Gold를 얻습니다.
* 유저가 사용할 수 있는 버튼은 총 3개입니다.
  * Buy : 50 Gold를 지불해 랜덤한 타워를 건설합니다. Buy 버튼을 클릭한 후 건설가능한 곳을 클릭하면 해당 지역에 타워가 건설됩니다. 타워에 대한 정보는 아래 표에서 확인 가능합니다.
  * Sell : 자신이 소유한 타워를 매각하고 건설 비용의 50%인 25 Gold를 돌려받습니다. Sell 버튼을 클릭한 후 보유중인 타워를 클릭하면 해당 타워가 매각됩니다.
  * Cancel : Buy과 Sell의 행동을 취소합니다. Buy 버튼을 클릭하거나 Sell 버튼을 클릭했을 때 해당 행동을 원하지 않는 경우 Cancel 버튼을 눌러 취소할 수 있습니다.
* 
### About Game
**Tower Status**
Lv | Probability | Attack | Range
-- | ----------- | ------ | -----
Lv1 | 50% | 5 | 4 Tiles
Lv2 | 45% | 10 | 6 Tiles
Lv3 | 4% | 30 | 8 Tiles
Lv4 | 1% | 50 | All

**Monster Status**
Round | Hp
----- | --
1 | 50
2 |
3 |
4 |
5 |
6 |
7 |
8 |
9 |
10 |

### 

### Reference
* 화면 오른쪽 버튼을 구현하기 위하여 아래 자료를 참고하였습니다
* https://blog.naver.com/jwjung0907/222207701304

### LICENSE
* Pygame is an open-source library licensed under the [GNU LGPL LICENSE v2.1](https://www.pygame.org/docs/LGPL.txt)
* All Used Images are open-source images licensed under [OGA-BY 3.0 LICENSE](https://static.opengameart.org/OGA-BY-3.0.txt) and [CC-BY 3.0 LICENSE](https://creativecommons.org/licenses/by/3.0/)
  * OGA-BY 3.0 is a license based on CC-BY 3.0 that removes that license's restriction on technical measures that prevent redistribution of a work. You can get more infromation about OGA-BY 3.0 LICENSE in the link
  * https://opengameart.org/content/grass-textures-tiles
  * 
* This project is licensed under the GNU LGPL License v2.1 as same Pygame
