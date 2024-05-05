# SMART_FARM_PROJECT

# 1. 문제 상황
기술이 발전함에 따라, 농업의 기술 또한 발전하고 있다. 이러한 농업 기술의 발전은 농작물의 품질을 향상시키는데 국한되지 않고, 생산과정을 자동화하는 것으로 이어지고 있다. <br>
농작물을 성장 시키기 물, 햇빛, 온도, 토양을 조절할 필요가 있다. 이번 프로젝트에서는 이러한 4가지 요소들을 관리하는 장치를 만들어볼 예정이다.

# 2. 관련 자료

## 1) 온도와 습도
농작물이 자라기 위해 1차적으로 필요한 것은 바로 온도와 습도이다.
농작물이 자라기 위해 필요한 온도와 습도는 농작물의 종류에 따라 상이한다.<br>
고온성 채소의 경우 가지, 고추, 박 등의 채소가 있는데 이러한 채소들의 경우 약 18~26C 정도를 유지하며<br>
저온성 채소의 경우 배추, 양배추, 무 등의 채소로 약 10 ~ 18C 정도를 유지한다.<br>

습도 또한 농작물의 종류마다 요구하는 습도가 다르다. <br>
일반적인 식물의 경우에는 40%이상의 습도가 요구되지만 물을 싫어하는 다육식물의 경우 30-40%
<br>관엽식물의 경우 50-60%, 고사리과 식물에게는 70%이상의 습도가 필요하다.

## 2) 햇빛
식물을 키우기 위해 무조건 햇빛이 필요한 것은 아니다. <br>
식물이 광합성을 하기 위해서는 최소한의 빛의 세기가 필요한데 빛의 세기가 최소 20000LUX 이상이 되어야 식물이 광합성을 할 수 있다. 햇빛은 약 60000LUX이다. <br>
인공적으로 식물에게 빛을 주기위해 가정에서 사용하면 형광등을 생각할 수 있는데, 일반적으로 가정에서 사용하는 형광등의 경우 50-200LUX정도로 식물을 키우기에는 부적합하다.<br>
하지만 최근 식물을 광합성 할 수 있게 해주는 광합성 LED가 시판되어 이것을 이용하면 햇빛 없이도 식물을 키울 수 있다.<br>

## 3) 토양
식물이 자라기 위해서는 물과 햇빛뿐만 아니라 영양분도 필요하다. 식물은 이러한 영양분을 흙을 통하여 얻는다.<br>
식물이 생장하기 위해 필요한 영양분은 다양하지만 가장 우선순위는 C(탄소),H(수소),O(산소)이다. <br>

# 3. 관련 기술

## 1) 온습도 센서
<img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMzA0MTVfMTY1%2FMDAxNjgxNTQzNzk5ODc0._6CDoY9P-OMB7uyUZU2HdG-zVHShC23jDSVHSWqT1xQg.ISKEngzegD6rJI0M6_G4W_HTTM2Ef4NuzUe8dLq8GRkg.JPEG.pmhsky8268%2F%25B4%25D9%25BF%25EE%25B7%25CE%25B5%25E5_%25281%2529.jpg&type=a340">
이번 프로젝트에서 사용할 온습도 센서는 DHT11이다. <br>
이 센서의 연결포트는 vcc(+) 와 gnd(-) 그리고 input으로 이루어져있다. 센서의 작동 원리에 대해서는 자세하게 기술하지 않겠다. <br>
센서에서 들어온 값을 아두이노를 통하여 내가 원하는 화씨(H) 또는 도씨(C)로 바꾸어 사용이 가능하다.<br>
이번 프로젝트에서는 이 온습도 센서를 사용하여 온도와 습도를 확인할 것이다.<br>

- 장점
  1. 사용이 간편하다.
  2. 가격이 저렴하다.
  3. 요구하는 전력이 작다
- 단점
  1. 새로운 온도를 받는데 2초의 딜레이가 존재한다
## 2) 조도 센서
<img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDA0MDdfMyAg%2FMDAxNzEyNDkyODUxMDUz.sDHQVqHD377uvxSmzx10xKH7M_xdGcWQnjGTXzjSmGwg.ibjOXA3EhEoW2FsG27NHKfSVt01AKI0wxzdnfu_mWKQg.JPEG%2F%25C1%25B6%25B5%25B5%25BC%25BE%25BC%25AD.jpg&type=a340">
이번 프로젝트에서 사용한 조도 센서는 cds 조도 센서이다. <br>

## 3) 펌프 모듈

## 4) 릴레이 모듈 

# 4. 알고리즘
## 1) 습도 관리 알고리즘

## 2) 온도 관리 알고리즘

## 3) 조도 관리 알고리즘

# 5. 구현

# 6. 결론 및 보안
