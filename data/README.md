본 태스크를 위한 데이터로, 일간베스트와 오늘의 유머 등 각종 커뮤니티 사이트의 댓글과 연예뉴스 댓글을 활용하였다. 총 데이터 수는 11,503건이며 train set과 test set을 9:1로 나누어 각각 10,353건, 1,150건으로진행하였다.

문장의 내용에 따라 정상 데이터는 ‘0’으로, 욕설 및 폭언 데이터는 ‘1’로 구분하였다. 정상 데이터와 폭언 데이터는 각각 7426건, 4077건으로 비율은 65:35이다. 각 데이터의 예시 문장은 <그림 6>에 나타내었다.

- 각종 커뮤니티 사이트 댓글 : https://github.com/2runo/Curse-detection-data
- 한국 연예뉴스 댓글 : https://github.com/kocohub/korean-hate-speech