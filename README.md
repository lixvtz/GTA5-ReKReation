# ReKReation
ReCreated AutodeskScaleform fontset for Grand Theft Auto V Legacy
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/CHARACTER_SELECTION.png?raw=true)

## 소개  
GTA5는 언어 설정 시 폰트 매핑 파일과 해당 언어용 폰트 라이브러리 단 하나를 로드합니다.  
예컨대 Grand Theft Auto V의 언어를 한국어로 설정할 경우, 게임은 중문간체, 중문번체, 일본어, 영어, 한국어 폰트 라이브러리 중 한국어 폰트 라이브러리만 로드합니다.  

라이브러리 파일에는 게임에서 필요로 하는 문자를 표시하기 위해 여러 폰트셋이 들어있는데, 한국어의 경우 실제 자막을 표시하기 위한 폰트로 모든 상황에서 **HYRKorean**을 사용합니다.  
**HYRKorean**은 굴림체와 같이 투박하고 세련되지 않았습니다.

이러한 폰트는 특히 **GTA 온라인 레거시** 환경의 특성을 충분히 반영하지 못합니다. 해당 폰트는 한국어 이외의 문자를 제대로 지원하지 않아 글로벌 채팅이 불가능하고, 표준 한국어 대비 적은 글리프 지원, 자모 글리프조차 없기 때문에 인해 오타발생 시 글자 자체가 만들어지지 않습니다. 이로 인해 실시간 소통이 중요한 환경에서 플레이어가 불편함을 겪습니다.

lixvtz의 **ReKReation**는 이러한 문제를 해결하기 위해 **GTAV 레거시**와 **GTA 온라인 레거시** 모든 경우를 생각하고 제작되었습니다. 기본 라이브러리에 있는 폰트를 모두 차세대 폰트로 변경하고, 각각의 위치에 알맞은 폰트를 적용하여 게임 플레이 경험을 향상시킵니다.

---

## 사용 방법  
### 자동 설치  
.oiv 파일을 이용하여 설치를 간단히 자동화할 수 있습니다.  

1. 제공된 **ReKReation_[version].oiv** 파일을 사용해 OpenIV를 통해 설치합니다.  

### 수동 설치  
1. 아래 파일들을 **ReKReation 라이브러리**로 교체합니다.  
   - `GTAV > update > update.rpf > x64 > data > cdimages > scaleform_platform_pc.rpf > font_lib_efigs_pc.gfx`  
   - `GTAV > update > update.rpf > x64 > data > cdimages > scaleform_platform_pc.rpf > font_lib_korean_pc.gfx`  
   - `GTAV > update > update.rpf > common > data > ui > fontmap.xml`  

2. 게임을 실행하여 변경된 폰트를 확인합니다.  

---

## 효과  
1. **HYRKorean 폰트**가 **차세대 폰트**로 대체되어 가독성이 대폭 향상됩니다.  
2. UI 요소와 자막이 각각의 위치에 각각 알맞은 폰트로 출력됩니다.  
 - 일반 자막의 경우 **NanumBarunGothic**, 지역 이름의 경우 **Nanum Pen Script**, 액센트의 경우 **NanumBarunGothic Bold**, **SUIT**를 사용합니다.
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/LEGAL.png?raw=true)
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/GTAV_ONLINE.GFX.png?raw=true)
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/CHARACTER_SELECTION.png?raw=true)
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/WEAPON_SELECTION_HUD.png?raw=true)
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/ARMORY.png?raw=true)
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/MISSIONCONTROLLER.png?raw=true)
![title](https://github.com/lixvtz/GTA5-ReKReation/blob/main/README/images/WASTED.png?raw=true)
3. **GTA 온라인**에서 한국어 채팅의 가독성이 향상되며, 영어로 설정된 상태에서도 한국어 채팅이 가능합니다.
- 자음, 모음만으로 채팅을 할 수 있습니다.
- 일본어, 중국어 등 채팅을 보고 쓸 수 있습니다. 
4. 게임 내 UI와 자막 디자인이 라틴 유저들과 거의 동등한 수준으로 개선됩니다.  

---

이 프로젝트는 **Grand Theft Auto V Legacy**, **Grand Theft Auto Online Legacy**의 한글 폰트를 개선하여 플레이어들의 경험을 향상시키기 위해 시작되었습니다. 함께해주셔서 감사합니다!  
