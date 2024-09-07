# Git 컨벤션 및 사용법

#### :smiley_cat:Git 초기 사용법
초기 설정에 시간 뺏기지 않도록 가이드라인 작성했습니다. 문제 생기거나 잘 안되는 부분 있으면 바로바로 물어보세요!

1. [원본 저장소](https://github.com/wxxhyeong/Cross_FIT)에서 fork
   
   ![image](https://github.com/wxxhyeong/kb-study/assets/78301292/68a993ed-db01-4e58-9e10-4f6eeda95245)


3. 작업할 폴더에서 우클릭으로 git bash 또는 명령 프롬프트로 repo를 저장할 경로로 이동
   ![image](https://github.com/user-attachments/assets/d7d1f514-ced8-4bde-a2be-2f1ae1ddfdc1)
      ![image](https://github.com/user-attachments/assets/ff7396f5-6a6e-4dad-b644-1e1298bf0544)<br>
   ![image](https://github.com/user-attachments/assets/43c022ec-db06-45f0-a4fc-a333edffaf99)
  
5. git clone 후 clone한 폴더로 이동
   
   ```git clone `원본 Repo말고 fork한 자신의 Repo주소'``` 입력
   
   ![image](https://github.com/user-attachments/assets/96d13bb9-489a-448b-850e-dcc8055eab3d)


7. 자신의 로컬 환경에서 이름으로 브랜치 생성 후 작업하기

   ```
   ex)
   git branch woohyeong // pc에 branch 생성 ※원격 Repository 환경에 생성된 것은 아님
   git checkout woohyeong // 작업할 브랜치로 전환 (main -> woohyeong)
   ```

8. 작업 후 push

   ```
   git add .   // 작업한 내용을 stage로 올리기
   git commit -m"message"   // commit message 작성
   git push origin woohyeong // 원격에 자신의 이름 branch가 있으면 거기에 push 없으면 자동으로 branch가 생성되며 push
   ```
   ![image](https://github.com/wxxhyeong/kb-study/assets/78301292/6403b0f7-3690-425e-af89-a01eb78843ab)

9. push 이후 web에 원격 저장소(repository)로 이동하여 pull request 작성
   ![image](https://github.com/wxxhyeong/kb-study/assets/78301292/1483839a-743f-4970-9098-2d962421d6d0)
