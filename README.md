# db_datagokr

* 데이터 활용시 본인 및 팀원이 편하게 이용할 수 있도록 모아두는 레포

* Python Pandas에서 아래와 같이 주소를 활용하여 바로 불러들일 수 있음
```python
  # 한국광해광업공단_광종별 소비현황에 대한 주소를 하단 `데이터 현황`에서 url부분에 붙여넣기
  url = 'https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_consume.csv'
  pd.read_csv(url, encoding='cp949', low_memory=False)
```

* 유의사항 : README.md(설명용 파일)에서 데이터 현황 항목은 늘 맨 밑에 두기 
  (업데이트일자 자동업데이트를 위함)

* 수동저장데이터
  * BDI(Baltic Dry Index)
https://raw.githubusercontent.com/KR9268/db_datagokr/main/Baltic_Dry_Index_Historical_Data.csv

  * UN Comtrade (산화코발트(282200), 황산코발트(283329)) **since 2011**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/282200,283329_merged(since2011).csv
  * UN Comtrade (산화코발트(282200), 황산코발트(283329)) **since 2021**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/282200,283329_merged(since2021).csv

  * UN Comtrade (산화/수산화리튬(282520), 탄산리튬(283691)) **since 2011**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/282520,283691_merged(since2011).csv
  * UN Comtrade (산화/수산화리튬(282520), 탄산리튬(283691)) **since 2021**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/282520,283691_merged(since2021).csv

  * UN Comtrade (산화/수산화니켈(282540), 황산니켈(283324)) **since 2011**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/282540,283324_merged(since2011).csv
  * UN Comtrade (산화/수산화니켈(282540), 황산니켈(283324)) **since 2021**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/282540,283324_merged(since2021).csv

  * UN Comtrade (이산화망간(850610)) **since 2011**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/850610_merged(since2011).csv
  * UN Comtrade (이산화망간(850610)) **since 2021**
https://raw.githubusercontent.com/KR9268/db_datagokr/main/850610_merged(since2021).csv


* 데이터 현황

  *  2024-07-30업데이트 : 한국광해광업공단_광종별 소비현황
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_consume.csv
  *  2024-07-30업데이트 : 한국광해광업공단_광종별_국가별_생산량
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_product_country.csv
  *  2024-07-30업데이트 : 한국광해광업공단_광종별 국내 수출입 현황
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_local_import_export.csv
  *  2024-07-30업데이트 : 한국광해광업공단_텅스텐가격예측데이터
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_eprice_tungsten.csv
  *  2024-07-30업데이트 : 한국광해광업공단_코발트가격예측데이터
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_eprice_cobalt.csv
  *  2024-07-30업데이트 : 한국광해광업공단_망간가격예측데이터
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_eprice_manganese.csv
  *  2024-07-30업데이트 : 한국광해광업공단_리튬가격예측데이터
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_eprice_lithium.csv
  *  2024-07-30업데이트 : 한국광해광업공단_수급안정화지수_코발트
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_procureidx_cobalt.csv
  *  2024-07-30업데이트 : 한국광해광업공단_수급안정화지수_리튬 
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_procureidx_lithium.csv
  *  2024-07-30업데이트 : 한국광해광업공단_수급안정화지수_니켈
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_procureidx_nickel.csv
  *  2024-07-30업데이트 : 한국광해광업공단_코발트 시장위험지수
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_marketidx_cobalt.csv
  *  2024-07-30업데이트 : 한국광해광업공단_리튬 시장위험지수
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_marketidx_lithium.csv
  *  2024-07-30업데이트 : 한국광해광업공단_국가별 광종 수출입 현황
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_global_import_export.csv
  *  2024-07-30업데이트 : 한국광해광업공단_광종별 매장량
https://raw.githubusercontent.com/KR9268/db_datagokr/main/komir_burried.csv
