# 以 Github 為圖床 的 PicGo 設置流程

## 1 建立一個新的 Repository

**要注意 Repository 要設為 Public**
[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20143355.jpg)](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20143355.jpg)

## 2 取得 token

右上角點選大頭貼，選`Settings`
[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20144011.png)](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20144011.png)

左邊欄位拉到為下面，點選`Developer settings`
[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20144249.png)](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20144249.png)

依序點選
[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20144515.png)](<https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-12-03%20144515.png>)

填寫`token`用途，並點選`repo`
![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203145401065.png)

接著拉到最下面，點`Generate token`
[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203145627936.png)](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203145627936.png)

將紅框內的`token`複製起來，`token`只會出現這一次，千萬別弄丟
[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203145850945.png)](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203145850945.png)

## 3 配置 PicGo 的 github 圖床設定

[![](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203150032951.png)](https://raw.githubusercontent.com/reese60525/ForPicGo/main/Pictures/20241203150032951.png)

1. 圖床配置名：圖床名稱，可以隨便取。
2. 設定倉庫名稱：格式必須是`github username/repository name`。
3. 分支名稱：如果分支當初設定是`main`，那麼這裡就填`main`，如果是`master`，那麼這裡就填`master`。
4. 設定Token：將剛剛複製的`token`貼上。
5. 設定儲存路徑：這指的是要將圖片放在`repository`中的哪裡，假設我想放在`repository/img`資料夾下，那麼這裡就填`img/`。
6. 設定自訂網址：沒研究，留白也不影響。
