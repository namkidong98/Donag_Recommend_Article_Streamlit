# Donag_Recommend_Article_Streamlit

# Directory Tree
```
streamlit/
├── model/
│   ├── bm25_model.json    # 학습된 bm25 모델
│   ├── bm25_model.py      # Kiwi_Tokenizer, Custom_BM25 모델 정의
│   └── custom_dict.txt    # Kiwi 형태소 분석기용 커스텀 사전(추출한 NER의 유효한 셋으로 구성) 
├── app.py                 # Streamlit App
├── milvus_connect.py      # Milvus 연결 
├── inference.py           # 추론에 필요한 함수들
├── requirements.txt       # 의존성
├── .env                   # 환경 변수 파일  
└── venv/                  # 가상 환경
```

# .env
```
UPSTAGE_API_KEY = ""
OPENAI_API_KEY = ""
```

# 실행 명령어
```
streamlit run app.py --server.port 8000 --server.runOnSave true
```

# 추가 자료
https://github.com/namkidong98/Donga_Recommend_Article
