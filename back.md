# StartLuo
* File 可能改為 CDN (String)
## 官網主頁
```
{
  imageUrl: File, 背景圖片
  events: [
  {
    titleImage: File, 主題名稱
    image: File, 左圖
    startTime: String, 開始時間(時間格式)
    btnImage: File, 按鈕
    link: String, 按鈕連結
  },
  {
    titleImage: File, 主題名稱
    image: File, 左圖
    startTime: String, 開始時間(時間格式)
    btnImage: File, 按鈕
    link: String, 按鈕連結
  }
  ]
}
```

## 發財開始囉
```
{
  imageUrl:File, 背景圖片
  detailImage: File, 活動資訊 (待確認)
  detailImage_phone: File, 活動資訊_手機 (待確認)
  eventRule: String, 活動規則
  titleImage: File, 主題名稱
  startTime: String, 開始時間(時間格式)
  timeText: String, 活動時間(用戶自訂義內容)
  locationText: String, 活動地點(用戶自訂義內容)
  btnImage_1: File, 按鈕1
  btnImage_2: File, 按鈕2
  link_1: String, 按鈕連結1
  link_2: String 按鈕連結2
}
```

## 賺錢開始鑼
```
{
  imageUrl:File, 背景圖片
  detailImage: File, 活動資訊 (待確認)
  detailImage_phone: File, 活動資訊_手機 (待確認)
  eventRule: String, 活動規則
  titleImage: File, 主題名稱
  startTime: String, 開始時間(時間格式)
  timeText: String, 活動時間(用戶自訂義內容)
  locationText: String, 活動地點(用戶自訂義內容)
  btnImage_1: File, 按鈕1
  btnImage_2: File, 按鈕2
  link_1: String, 按鈕連結1
  link_2: String 按鈕連結2
}
```

## 最新活動
```
{
  imageUrl: file, 背景圖片
  titleImage: file, 主題名稱
  content: String, 內文 ** 26 碼以內
  cards: [
    {
      imageUrl: File, 圖片
      startTime: String, 活動時間
      locationText: String, 活動地點
      titleText: String, 活動主題
      btnText: String, 按鈕文字
      link: String 按鈕連結
    },
  ]
}
```

## 音樂祭活動
```
{
  imageUrl: File, 背景圖
  titleImage: File, 主題名稱
  contentImage: File, 宣傳圖
  startTime: String, 開始時間(時間格式)
  timeText: String, 活動時間(用戶自訂義內容)
  locationText: String, 活動地點(用戶自訂義內容)
  btnImage: File, 按鈕
  link: String, 按鈕連結
}
```

## 沙漏活動
```
{
  eventRule: String, 活動規則
}
```

## 皂飛車活動
```
{
  timeText: String, 活動時間(用戶自訂義內容)
  locationText: String, 活動地點(用戶自訂義內容)
  eventRule: String, 活動規則
  btnImage: File, 按鈕
  link: String, 按鈕連結
}
```

## 品牌與名人
```
{
  cards: [{
    ImageUrl: File, 左圖
    titleText: String, 左主題
  },
  {
    ImageUrl: File, 右圖
    titleText: String, 右主題
  }]
  brands: [Flie, Flie, ...] 品牌列表
}
```

## 服務條款
```
{
  personalInfo: String, 個人資料
  gameManage: String, 遊戲管理
  usersContract: String, 使用者契約
  returnHandle: String, 退貨處理
  privacy: String, 隱私權
}
```
