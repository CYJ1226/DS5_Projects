# Streamlit Page
<img width="648" height="531" alt="image" src="https://github.com/user-attachments/assets/220e632e-e23a-4055-8694-590589c5caad" />
<img width="644" height="813" alt="image" src="https://github.com/user-attachments/assets/1b88fdf8-7c08-4f93-a040-a21f429198ec" />

---

# 성능 향상 시도
### 1. Base
- 하이퍼 파라미터
    - epochs=5
    - learning_rate= 0.0001
    - dropout= 0.4
    - batch_size = 2048
    - embed_dim= 16
- 결과
    - mymodel ndcg :  0.66213
    - mymodel hitrate :  0.6303
 
### 2. epochs, learning_rate 변경
- 하이퍼 파라미터
    - epochs=7
    - learning_rate= 0.0005
    - dropout= 0.4
    - batch_size = 2048
    - embed_dim= 16
- 결과
    - mymodel ndcg :  0.66252
    - mymodel hitrate :  0.63084
      
### 3. dropout 변경
- 하이퍼 파라미터
    - epochs=7
    - learning_rate= 0.0005
    - dropout= 0.2
    - batch_size = 2048
    - embed_dim= 16
- 결과
    - mymodel ndcg :  0.66177
    - mymodel hitrate :  0.63051
 
### 4. embed_dim 변경
- 하이퍼 파라미터
    - epochs=7
    - learning_rate= 0.0005
    - dropout= 0.4
    - batch_size = 2048
    - embed_dim= 32
- 결과
    - mymodel ndcg :  0.66556
    - mymodel hitrate :  0.63213
 
### 5. batch_size 변경
- 하이퍼 파라미터
    - epochs=7
    - learning_rate= 0.0005
    - dropout= 0.4
    - batch_size = 1024
    - embed_dim= 32
- 결과
    - mymodel ndcg :  0.66763
    - mymodel hitrate :  0.63354
