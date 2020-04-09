## 초아봇 명령어 도움말

초아봇을 최초 초대시 접두사(명령어 앞에 붙는 글자)가 `ㅊ`으로 설정됩니다
초아봇의 명령어에는 항상 접두사가 붙습니다 `ㅊ명령어`형태
모든 가이드는 **기본접두사(ㅊ)** 를 기준으로 작성되었습니다
**/(슬래쉬)** 표시는 좌우 단어중 아무거나 입력해도 된다는 설명 입니다

초아봇에 대한 지원은 [팀파스텔 공식 디스코드](https://discord.gg/Jz6pmBh) 에서 받으실수 있습니다

## 초아봇 내부 권한체계 관련
초아봇은 이용자별로 내부 권한체계를 가지고 있습니다

**ban**
>팀파스텔로부터 이용제제를 받은 사용자

**none** 
>등록되지 않은 사용자

**user**
>등록된 일반 사용자

**teampastel**
>봇 관리권한을 가진 관리자

## 초아와 대화하기 기능
`초아야 (할말)` 로 초아와 대화할 수 있습니다

### ㅊ핑
```Markdown
# 봇의 핑(지연시간)을 보여줍니다
* 초아봇권한 : none 이상
```

### ㅊ가입
```Markdown
# 초아봇 이용을위한 사용자등록을 합니다
* 초아봇권한 : none 이상
```

### ㅊ나는/나는?
```Markdown
# ㅊ초아봇이 보여주는 본인의 프로필입니다
* 초아봇권한 : none 이상
```

### ㅊ프로필 [@유저]
```Markdown
# 초아봇이 보여주는 `@유저`의 프로필입니다
* 초아봇권한 : user 이상
```

### ㅊ코로나
```Markdown
# 코로나19의 국내현황을 보여줍니다
* 초아봇권한 : user 이상
```

### ㅊ접두사 [접두사] (서버내에서만 작동)
```Markdown
# 초아봇의 명령어 앞에붙을 prefix를 설정합니다
 설정한 접두사는 해당 서버 내에서만 반영됩니다
* 초아봇권한 : user 이상
* 서버내 권한 : 관리자
```

## ㅊ초아봇 번역기능
1.초아봇 변역기능은 카카오 오픈 API를 통해서 이루어집니다
```Markdown
* 초아봇권한 : user 이상
```
### ㅊ한영 [번역할 내용] 
> 한국어를 영어로 번역합니다

### ㅊ영한 [번역할 내용] 
> 영어를 한국어로 번역합니다

### ㅊ한일 [번역할 내용] 
> 한국어를 일본어로 번역합니다 

### ㅊ일한 [번역할 내용] 
> 일본어를 한국어로 번역합니다

추후 **다른언어**또한 추가할 예정입니다

## 초아봇 이미지 검색기능
1.초아봇 이미지검색 기능은 카카오 오픈 API를 통해서 이루어집니다

### ㅊ이미지 [검색어]
```Markdown
# 검색어에 대한 다음 이미지검색 상위 10 결과에서 랜덤으로 하나를 보여줍니다
* 초아봇권한 : user 이상
```

## 초아봇 단축 url기능
1.초아봇 url단축 기능은 네이버 오픈 API를 통해서 이루어집니다

### ㅊ단축 [url]
```Markdown
# url을 단축된 형태로 보여줍니다
* 초아봇권한 : user 이상
```

## 초아봇 사전검색
1.초아봇 url단축 기능은 네이버 오픈 API를 통해서 이루어집니다

### ㅊ사전 [검색어]
```Markdown
# 검색어에대한 네이버 사전 검색결과를 보여줍니다
* 초아봇권한 : user 이상
```


## 초아봇 돈 기능
1.추후 돈연관 기능을 업데이트할 예정입니다

### ㅊ돈
```Markdown
# 현재 초아코인의 소지량을 보여줍니다
* 초아봇권한 : user 이상
```
### ㅊ돈줘
```Markdown
# 25개에서 50개사이의 초아코인을 랜덤하게 지급합니다
* 초아봇권한 : user 이상
* 쿨타임 : 2분
```
### ㅊ도박
```Markdown
# 소지중인 초아코인을 모두 사용하여 도박합니다(0배 ~ 5배)
* 초아봇권한 : user 이상
```


## 초아봇 레벨 기능
추후 레벨연관 기능을 업데이트할 예정입니다
1. 초아봇의 경험치는 초아가 확인할수있는 채널 아무곳에나 채팅을 입력시 랜덤의 경험치를 획득합니다
1. 도배와 부정 획득을 방지하기 위해 분당 1회의 채팅만 경험치를 획득할수 있습니다

### ㅊ레벨
```Markdown
# 현재 레벨과 경험치를 보여줍니다
* 초아봇권한 : user 이상
```

