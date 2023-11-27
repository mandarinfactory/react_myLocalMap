# react_myLocalMap(동네지도)

## 🖥️ 프로젝트 소개
reactJS를 기반으로 네이버지도API, 공공데이터API(소상공인시장진흥공단_상가(상권)정보_API)를 이용해서 지역 기반 상가정보를 알려주는 사이트입니다.

## 🧭 웹사이트
https://react-mylocalmap.web.app/

## 🕰️ 개발 기간
- 23.07월 - 23.09월

## ⚙️ 개발환경
- 바닐라JS
- React JS
- tailwind CSS
- firebase(배포)

## ⚙️ 사용API
- 네이버지도API(https://www.ncloud.com/product/applicationService/maps)
- 공공데이터API(https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15012005)

## 📌주요 기능
### 메뉴클릭시, 상점리스트 및 지도에 마커생성 - <a href="https://github.com/mandarinfactory/react_movieSearch/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EB%B0%95%EC%8A%A4%EC%98%A4%ED%94%BC%EC%8A%A4,--%EC%83%81%EC%98%81%EC%98%88%EC%A0%95%EC%9E%91)">위키</a>
- 메뉴클릭시, 해당 상가분류에 따라 지도내에 있는 상가리스트를 데이터로 받게 했습니다.
- 해당 데이터를 이용해서 오른쪽에 상점리스트, 지도에는 마커를 생성시키게 구현했습니다.
- 상가데이터는 공공데이터API를 이용했으며, 지도는 네이버지도 API를 이용했습니다.

### 리스트 또는 마커 클릭시 해당 상점으로 이동하게 구현 - <a href="https://github.com/mandarinfactory/react_movieSearch/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EC%98%81%ED%99%94%EA%B2%80%EC%83%89)">위키</a>
- 각각 상점리스트나 마커를 클릭하면 해당 상점의 마커를 지도의 가운데로 이동시키게 구현했습니다.
- 또한, 클릭시 상세정보들이 추가적으로 나오게 modal창을 구현했습니다.
- 해당 modal창에서의 사진들은 메뉴별로 하드코딩으로 넣었습니다.

### 도시검색시 구글API를 이용해 이동하게 구현 - <a href="https://github.com/mandarinfactory/react_movieSearch/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EC%98%81%ED%99%94%ED%81%90%EB%A0%88%EC%9D%B4%EC%85%98)">위키</a>
- input란에 한국 도시만 검색하게 제한을 두고 검색시 아래 연관 검색어로 나오게 구현했습니다.
- 관련 검색어내 원하는곳을 클릭시, 경/위도를 데이터로 가져와 네이버지도에서 이동하게끔 구현했습니다.
