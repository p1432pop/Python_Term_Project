## Random Tower Defense
### Basic Information
* 컴퓨터공학과 21101237 한정현
* Open-Source를 활용한 디펜스 게임

### Prerequisite
* 파이썬 개발 환경
* Pygame, math, random packages

### How To Play
* 게임의 목표는 타워를 설치해 몬스터가 목표 지점에 도달하기 전에 섬멸시키는 것입니다.
* 게임은 총 10 라운드로 진행되며 현재 라운드는 오른쪽 상단에 표기됩니다. 
* 게임을 실행하고 10초간 타워를 건설할 수 있는 시간이 주어집니다.
* 이후 각 라운드마다 1초에 1마리씩 총 20마리의 몬스터가 등장하며 마지막 몬스터가 소환된 시점을 기준으로 20초 후 다음 라운드가 진행됩니다. 각 라운드별 몬스터의 체력을 아래 표에서 확인 가능합니다.
* 모든 몬스터는 왼쪽 상단에서 등장하며 길을 따라 오른쪽 하단에 있는 목표 지점으로 이동합니다.
* 게임 시작시 :heart: 30 Life와 :yellow_circle: 150 Gold를 가지고 시작하며 현재 Life와 보유중인 Gold는 오른쪽 상단에 표기됩니다.
  * 몬스터가 목표 지점에 도달하기 전까지 처치하지 못할 경우 :heart: 1개가 소모되며 Final 라운드가 끝나기 전에 :heart:를 모두 소모할 경우 게임에서 패배합니다.
  * :yellow_circle:Gold는 타워를 설치하거나 판매할 때 사용되는 화폐이며 몬스터 처치시 :yellow_circle:5 Gold를 얻을 수 있습니다.
* 플레이어가 사용할 수 있는 버튼은 총 3개입니다.
  * Buy : :yellow_circle:50 Gold를 지불해 랜덤한 타워를 건설합니다. Buy 버튼을 클릭한 후 건설가능한 곳을 클릭하면 해당 지역에 타워가 건설됩니다. 타워의 능력치는 오른쪽 하단에 표기되며 더 자세한 정보는 아래 표에서 확인 가능합니다.
  * Sell : 자신이 소유한 타워를 매각하고 건설 비용의 50%인 :yellow_circle:25 Gold를 돌려받습니다. Sell 버튼을 클릭한 후 보유중인 타워를 클릭하면 해당 타워가 매각됩니다.
  * Cancel : Buy과 Sell의 행동을 취소합니다. Buy 버튼을 클릭하거나 Sell 버튼을 클릭했을 때 해당 행동을 원하지 않는 경우 Cancel 버튼을 눌러 취소할 수 있습니다.
* 게임이 종료되면 화면에 점수를 표기합니다. 종료 시점의 Gold와 Life는 각각 1점 20점으로 환산됩니다.

### Details About Game
**Tower Status**
Lv | Probability | Attack | Range
-- | ----------- | ------ | -----
Lv1 | 60% | 5 | 4 Tiles
Lv2 | 34% | 10 | 6 Tiles
Lv3 | 5% | 30 | 8 Tiles
Lv4 | 1% | 50 | All

**Monster Status**
Round | Hp
----- | --
1 | 60
2 | 90
3 | 140
4 | 210
5 | 300
6 | 410
7 | 540
8 | 690
9 | 860
10 | 1050

### 

### Reference
* 화면 오른쪽 버튼을 구현하기 위하여 아래 자료를 참고하였습니다.
  * https://blog.naver.com/jwjung0907/222207701304
* 본 프로젝트에서 사용한 모든 이미지의 출처는 [OpenGameArt](https://opengameart.org/)에 있습니다. 각 이미지에 대한 정보는 아래 링크에서 확인할 수 있습니다.
  * [BackGround](https://opengameart.org/content/grass-textures-tiles)
  * [Tower]()
  * [Monster]()
  * [Gold]()
  * [Life]()
  * [Attack Motion]()
  * [Tower Information]()

### LICENSE
* Pygame is an open-source library licensed under the [GNU LGPL LICENSE v2.1](https://www.pygame.org/docs/LGPL.txt).
* All Used Images are open-source images licensed under [OGA-BY 3.0 LICENSE](https://static.opengameart.org/OGA-BY-3.0.txt) and [CC-BY 3.0 LICENSE](https://creativecommons.org/licenses/by/3.0/).
  * OGA-BY 3.0 is a license based on CC-BY 3.0 that removes that license's restriction on technical measures that prevent redistribution of a work. You can get more information about [OGA-BY 3.0 LICENSE](https://www.pygame.org/docs/LGPL.txt) in the link.
* This project is licensed under the GNU LGPL LICENSE v2.1.
