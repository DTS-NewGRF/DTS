# Diversity Train Set 다양성 열차세트 /DTS
**다양성 열차세트**는 <br>
약 2016년에 [YST set](https://github.com/evepoi/YST)에서 최초로 시작했다.<br>
2022년 4월 2일 YST에서 열차들이 나라별도 분리된 <br>
[한국열차세트 플러스](https://github.com/GBLINER/KoreanTrainSet_Plus), [일본열차세트 플러스](https://github.com/GBLINER/JapaneseTrainSet_Plus), [중국열차세트](https://github.com/GBLINER/ChineseTrainSet), 
[유럽열차세트](https://github.com/GBLINER/EuropeanTrainSet), [세계열차세트](https://github.com/GBLINER/WorldTrainSet), [가상열차세트](https://github.com/GBLINER/VirtualTrainSet)로 파생되었다.<br>
가상열차세트를 제외한 다른 셋은 여전히 파생셋으로 관리되고 있다.<br>
`[YST]는 중단되었다.`<br>

2023년 5월 `Derivative Train Set 파생형 열차세트 / DTS`로 다시 통합하여 진행을 시작했다.<br>
2024년 1월 `Diversity Train Set 다양성 열차세트 / DTS`로 이름을 변경하여 다양한 열차들을 수용하는데 적극적으로 추가진행하고 있다.ㅡㅁ<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
```
[1.39] 2024.01.22
[추가]
- [관광열차 그룹] 관광열차 그룹화 전용 디자인 추가

[변경]
- [한국 지하철] 열차 정렬 재정비 / 세부사항 인게임에서 확인.
```
## 인게임 등록
```
[1.35] 2024.01.01
[공지사항]
- [GRF 이름변경] 파생형 열차세트 -> 다양성 열차세트
- [삭제될 열차] 2024. 2월 삭제 공지. / 삭제열차, 도색명 강제 적용.

[추가]
- [DTS/3량] DMZ 도색
- [DTS/10량] 한국철도공사 5세대 사운드에 따른 도색 추가
- [DTS/3량] 포항영덕 도색
- [DTS/14량] DPX 추가 / 우편,귀금속, 상품 운반 / 윙바디 컨셉 적용

[변경]
- [DTS/5량] 해변관광열차 그래픽 수정.
- [KTX-산천] 사운드로 인한 도색 변경 통합
- [DTS] 한국철도공사 1세대 도색 변경 통합
- [DTS] 서울교통공사 1세대 일부 도색 변경 통합
- [DTS] 한국철도공사 2세대 도색 변경 통합
- [DTS] 서울교통공사 2세대 4000호대 도색 통합

[사운드]
- [DTS] 한국철도공사 5세대 소프트웨어 개선
- [DTS] CL-150, CL-180
```

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

## 저작권
이 NewGRF는 크리에이티브 커먼스 라이선스 v3.0 (CC-BY-NC-SA v3.0)을 따릅니다. <br>
이 프로젝트에 기여함은 이 라이선스에 동의함을 의미합니다. <br>
라이선스에 따라, 등록된 자료는 누구나 수정할 수 있습니다.
