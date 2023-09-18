# 필독!
이곳은 "원격저장소"로 **White의 컴퓨터 폴더(로컬저장소)** 와 연동 되어있습니다! **로컬저장소 폴더 삭제엄금!**

**로컬저장소명 : Pandain_Product_Dev**

**[유의사항]**
```
 1. 새로운 제품군을 생성할 때에는 "add new"폴더를 Copy하여 생성합니다.
 2. 영상의 경우 아래 [영상 삽입 방법]항목에서 코드 긁어옵니다. src 항목에 영상 경로 삽입.
```

**[영상 삽입 방법] - 각 플랫폼 마다 다름**
```
1. 공식몰(카페24)
<div class="dpage_wrap" style="margin: 0 auto 20px;">
   <iframe class="dpage_youtube" width="100%" height="100%" src="영상 url" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
</div>


2. 오늘의집
 <div style="position: relative; margin: 0 auto 20px; padding-bottom: 56.25%;">
   <iframe style="position: absolute; top: 0; left: 0;" src="영상 url" width="100%" height="100%" frameborder="0"></iframe></div>
</div>


3. 카카오(쇼핑, 선물하기)
<div class="cu-video">
  <div class="cu-video-aspect-ratio">
        <iframe src="영상 url"></iframe>
  </div>
</div>

```


**[공지사항 (연휴안내 등) 기준 HTML 코드]*
```
사운드판다 : <img src="http://gi.esmplus.com/raffinew/soundpanda/00A_top_common/01_notice/notice.gif" alt="사운드판다 공지사항">
판다지아 : <img src="https://gi.esmplus.com/raffinew/pandasia/00A_top_common/01_notice/pandasia_notice.gif" alt="판다지아 공지사항">
```
- 판다지아


## 업로드 방법

**[유실을 대비한 공용폴더 백업과 코드 백업방법 영상]**
[SOUNDPANDA_code](https://drive.google.com/drive/folders/1YXS5nTr0FRrZiL20rfLOcKGP6cGa8Dwo?usp=sharing, "SOUNDPANDA_code")


**[깃허브 명령어 정리]**   

깃허브 내 명령어는 무궁무진하지만 업로드와 다운로드에 관련된 명령어만 추가하겠습니다.
자세한 항목은 깃 공식 영어전문과 한국어로 정리되어 있는 게시물 링크 첨부합니다.

```
1. 현재 directory(로컬저장소)의 모든 파일을 Staging Area(원격저장소)로 이동
git add .

2. file들의 tracking 상태 보기 -> 업로드가 되었는지, 누락된게 있는지
git status

3. Staging 의 파일들 commit 하기 -> 수정내역 추적할 때 이 메시지로 구분
git commit -m "messsage(내용 아무거나 상관X)"

4. 저장소에 commit 반영하기 -> 로컬저장소에서 원격저장소로 업로드
git push origin 브랜치명 > git push origin sound


5. 저장소에서 commit 가지고 오기 -> 원격저장소에서 로컬저장소로 다운로드
git pull 

```

- [깃허브 명령어](https://eehoeskrap.tistory.com/666)
- [git origin(원문)](https://git-scm.com)

## 영상 픽셀값 (근사치, px단위)

|가로값|세로값|
|:--:|:--:|
|640|360|
|720|405|
|752|423|
|768|432|
|784|441|
|800|450|
|832|468|
|864|486|
|880|495|
|928|522|
|944|531|
|960|540|
|1008|567|
|1040|585|
|1440|810|




**git init 순서 백업**
init은 로컬저장소와 원격저장소를 서로 연결해 주는 명령어

**[명령어 순서 - 첫 연결 및 마스터 브랜치 생성]**
```
echo "# test" >> README.md
1.git init
2.git add README.md (. 는 모든 폴더 및 파일 업로드)
3.git commit -m "first commit(아무거나 써도 됨)"
4.git branch -M main (브랜치명을 설정, 여기서는 main이 곧 브랜치명)
5.git remote add origin https://github.com/pandaintdesign/폴더명.git
6.git push -u origin main (업로드 할 때 마지막에 브랜치명을 입력해 주세요. 이부분은 추후 업로드일 때도 똑같음)
```

**[업로드 하는 방법]**
```
1.git remote add origin https://github.com/pandaintdesign/폴더명.git
2.git branch -M main
3.git push -u origin main
```



이 필독서는 "마크다운 언어"로 만들어졌습니다.
수정 시에는 마크다운 "언어 문법"을 참고해주세요.
