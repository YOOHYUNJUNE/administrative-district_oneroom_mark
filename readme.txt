![geohash][https://github.com/YOOHYUNJUNE/administrative-district_oneroom_mark/blob/master/geohash_seoul.jpg]

### 본 코드는 코딩 교육과정에서 소규모 프로젝트 중 만든 코드이며 "크롤링", "판다스", "행정구역"연습 용도로만 사용되었습니다.
### 크롤링된 데이터에 대한 저작권은 직방에게 있습니다.
### 최신 행정구역코드와 다를 수 있습니다.


# 코드 기능
- 대학교 이름 검색시, 동일 행정구 내 원룸을 마커로 보여주고, 마커 클릭시 해당 매물 URL로 이동

# 코드 순서
1. 원룸 매물을 크롤링합니다.
2. 각 매물들에게 행정구코드를 부여해줍니다.
3. 원룸과 대학교 행정구 코드를 매칭시킵니다. 
4. 대학교 이름 검색 시 주변 원룸을 보여줍니다.

# 한계
1. 사용된 geohash 좌표가 서울 전체를 포함하지 못함
2. 대학교 검색시, 대학교 반경 거리가 아닌 "동일" 행정구 내 원룸만 검색

# GEOhash에 대해서
- 직방은 "geohash"라는 좌표를 이용합니다.
- 원룸매물의 개발자 도구를 크롤링했습니다.
- 서울의 경우 "wjdq", 'Wjdj", "wjdm"으로 지정했습니다.
- 세 좌표에 포함되지 않은 서울 지역도 있는 것으로 보이나, 산간지역으로 추정하여 좌표를 주가하지 않았습니다.


# 참고 사이트
- 크롤링: https://www.zigbang.com/home/oneroom/map
- 행정구역 코드 및 경계: https://github.com/vuski/admdongkor?tab=readme-ov-file
