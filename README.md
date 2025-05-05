⚠️ 본 프로젝트는 Colab에서 진행되었으며, 주요 코드는 아래 Colab 링크에서 확인하실 수 있습니다.
🧠 Riot API 기반 멜리오라 챔피언 빌드 분석 프로젝트
📌 프로젝트 개요
목적: 멜(Mel) 챔피언의 아이템 빌드와 상대 챔피언 조합에 따른 승률 분석
데이터: Riot API로 수집한 Diamond~Challenger 티어의 전적 데이터 (MatchData, TimelineData 포함)
기술 스택: Python, Pandas, Riot API, Google Colab

🔍 주요 기능
전적 데이터 수집 및 파싱 (matchId 기반)
챔피언별 타임라인 이벤트 분석 (아이템 구매 시점 추적)
초반 3개 아이템 빌드 조합 추출
상위 5위 상대 챔피언별 대응 빌드 선정 및 승률 비교
시각화/비율 분석을 통한 추천 빌드 도출

📂 프로젝트 파일
Google Colab 코드 보기 👉 
(데이터 수집) https://colab.research.google.com/drive/1zGQwEfYHnOtD6Wif_8eNCS_TsooPxyzD?usp=sharing
(데이터 분석) https://colab.research.google.com/drive/1HiS93hHSmd6zWgi9nOduYKKaE28HiDeq?usp=sharing
