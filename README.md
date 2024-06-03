# Diversity Train Set 다양성 열차세트 /DTS
![DTS_board](https://github.com/DTS-NewGRF/DTS/blob/minengallery/docs/DTS_board.png)
**다양성 열차세트**는 <br>
약 2016년에 [YST set](https://github.com/evepoi/YST)에서 최초로 시작했다.<br>
2022년 4월 2일 `[YST]는 중단되었다.`<br>
2023년 5월 `Derivative Train Set 파생형 열차세트 / DTS`로 다시 통합하여 진행을 시작했다.<br>
2024년 1월 `Diversity Train Set 다양성 열차세트 / DTS`로 이름을 변경하여 다양한 열차들을 수용하는데 적극적으로 추가진행하고 있다.<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
```
[1.49] 2024.06.04
[긴급버그수정]
- [관광열차] 정선아리랑 그래픽 위치 오류 수정.
```
```
[1.49] 2024.05.21
[긴급 버그 수정]
- [관광열차] 와인시네마열차 그래픽 위치 오류 수정.
```
```
[1.49] 2024.05.19
[추가]
- [광주교통공사] 1000호대
- [대전교통공사] 1000호대
- [한국철도공사] 8000호대 전기기관차

[변경]
- [그래픽] 신림선, 한국철도공사 3세대 2차분, 부산김해경전철
- [사운드] 부산김해경전철 수익사운드 변경
- [의정부경전철] 뒤집힘 방지 추가
- [용인경전철] 수익사운드 변경
- [서울교통공사] 9000호대 구매창 그래픽 수정
- [TGV] Thaylys PBKA 그래픽 수정
- [32bpp] 적용열차 기본 32bpp 그래픽 변경
```

## 인게임 등록
```
[1.39] 2024.02.01
[공지사항]
- DTS 오브젝트셋 깃허브 릴리즈 공개로 인해 DTS 내 오브젝트 2024년 3월 삭제예정 문구 강제 출력.
- [한국지하철] 열차 정비로 인한 삭제여부 2024년 3월 삭제 예정 강제 공지 및 삭제 그래픽 적용.

[추가]
- [관광열차 그룹] 관광열차 그룹화 전용 디자인
- [서울교통공사] 그룹화 전용 디자인
- [서울교통공사] 초기, 개조저항 신규
- [한국철도공사] 그룹화 전용 디자인 
- [신분당선] 1,2,3세대
- [RDC] 경북나드리 도색 
- [부산교통공사] 1000호대 1,2,3세대
- [부산교통공사] 2000, 3000호대
- [대구교통공사] 그룹화 전용디자인
- [대구교통공사] 1000, 2000호대

[변경]
- [한국 지하철] 열차 정렬 재정비 / 세부사항 인게임에서 확인.
- [서울교통공사] 1,4세대 9000호대 객차 편성 수정.

[사운드]
- [7000호대 디젤기관차] 정지 사운드 추가
- 일부 출발사운드 파일이름 변경 / 게임상 변화 없음
```

## Next 인게임 버전 : 1.50

## 등록기준
### 공통사항
기본 템플릿과 일치하지 않을 경우 적용이 보류된다. 하지만, 그외 자료는 제한을 두지 않고, 적용하고 있다.

### 깃허브 릴리즈 및 온라인컨텐츠 등록
기본 자료는 본 깃허브 릴리즈를 통해 메인 업로드를 기준으로 한다. <br>
릴리즈 등록시 프리 릴리즈가 아닌 최종 릴리즈로 등록된다. <br>
온라인 컨텐츠는 매달 등록되는것으로 정의한다. <br>
매달 기준 최종 깃허브 릴리즈가 온라인컨텐츠로 등록되는 것과 같다. <br>

## 개발
### 빌드하는 방법
이 NewGRF를 빌드하려면 [NML](https://github.com/OpenTTD/nml)과 **Python 3**이 필요합니다. <br> 
터미널 쉘에서 ``make``를 실행하세요. Windows 환경이라면, 그 전에 명령 프롬포트를 열고 ``bash``를 입력하세요.  <br>
``make clean``을 입력하면 모든 생성된 파일이 초기화됩니다.
