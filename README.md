<!-- problem-first-summary:start -->
**Huge Problem(Pain Point):** 여러 학습자가 작성한 C 실습 코드가 개인 환경에 흩어지면 진도와 시행착오를 함께 축적하기 어렵다.

**솔루션 한 줄 정의:** 주차·작성자·문제 단위 규칙과 PR 흐름으로 C 실습을 공동 아카이브한다.

**현재 상태:** 학습 아카이브

**문제 해결 중심의 사고 흐름**

1. **관찰** — 스터디 구성원의 실습 결과와 질문이 개인 파일에 머물러 서로의 풀이 과정을 찾기 어려웠다.
2. **선택** — 완성된 하나의 앱보다 제출 경로와 커밋 규칙을 통일하는 것이 먼저라고 판단했다.
3. **구현** — 주차·작성자·문제 기준의 저장 경로와 fork/PR 기반 공유 절차를 사용했다.
4. **검증과 한계** — 현재 저장소는 소수의 실습 산출물과 협업 절차를 보존한다. 학습 성과 비교는 별도 지표로 측정하지 않았다.
<!-- problem-first-summary:end -->

---
### ☃️ 2024 2학기 snow ball 고급 C 프로그래밍 스터디용 github ☃️

## 💢 규칙
1. commit 혹은 pull할 때는 양식 맞춰주기
   - 파일경로 **`"/2024_2_C_study/code/{자기이름}/{주차}/{파일 이름}"`**
   - 커밋 메세지 **`"{주차} 과제{번호}/{주제}실습문제 문제{번호}"`**

## ✅ 초기 설정
1. 초대 후 우측 상단의 `inbox📥`를 통해 **`accept invitation`** 클릭
2. 좌측 메뉴에서 본 리포지토리가 생긴 것을 확인할 수 있다.
3. 우측 상단에 **`fork`** 를 클릭<br/>
   <img width="198" alt="image" src="https://github.com/user-attachments/assets/c6b68ce5-4380-4335-b3fe-ac36bb72183b">


4. 우측 하단의 **`create fork`** 를 클릭
5. 자기 레포지토리가 생성된 것을 확인할 수 있다.

## ▶️ 사용 방법
**A) 자기 repository에 코드 업로드**

1. 우측 상단에 `+` 버튼을 통해 **`create new file`** 클릭  
   <img width="206" alt="image" src="https://github.com/user-attachments/assets/1d2574ff-61c3-49d8-9f07-de234a961ab8">


2. 우측 상단의 경로를 **`"/2024_2_C_study/code/{자기이름}/{주차}/{파일 이름}"`** 에 맞춰 작성
3. 아래 Edit에 코드 복사
4. **`commit changes`** 클릭  
   <img width="1226" alt="image" src="https://github.com/user-attachments/assets/f412da89-6235-4cd1-894e-2327b3f6d5eb">


5. **`commit message`** 를 **`"{주차} 과제{번호}/{주제}실습문제 문제{번호}"`** 에 맞춰 작성 후 **`commit changes`** 클릭  
   <p align="center">
      <img width="474" alt="image" src="https://github.com/user-attachments/assets/34169d15-2060-497d-a6e5-4379bb4ab12c">
   </p>

**B) base repository에 업로드**

1. 상단 바에서 **`pull requests`** 클릭
2. **`New pull request`** 클릭  <br/>
   <img width="1216" alt="image" src="https://github.com/user-attachments/assets/f708c684-48ee-433d-ae37-d802973981d3">


3. **`create pull request`** 클릭<br/>
   <img width="1200" alt="image" src="https://github.com/user-attachments/assets/783abb96-cf63-4239-bdb6-fe28ba55b6e4">

4. **`Add a title`** 은 변경하지 않고 **`Add a description`** 에 질문을 적어 **`create pull request`** 클릭  
   <img width="826" alt="image" src="https://github.com/user-attachments/assets/7642a0c9-e005-46aa-b71b-878a3fc43598">


5. [옵션] 아래와 같이 **`merge pull request`** 와 **`confirm merge`** 클릭  
   <img width="881" alt="image" src="https://github.com/user-attachments/assets/4ac1f1e7-3173-4823-81d3-022238cc597f">
   <img width="879" alt="image" src="https://github.com/user-attachments/assets/e67395e5-f96a-4fef-a40d-8607b260f718">

