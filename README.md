**まりお**  

**実行環境の必要条件**  
python >= 3.10  
pygame >= 2.1  

**ゲーム概要**  
マリオブラザーズを模したゲーム  

**ゲームの実装**  
***共通基本機能***  
ウィンドウと背景  

***担当追加機能***   
プレイヤー：操作キャラクターの動きに対するクラス  
マップ　　：ゲームマップの作製  
敵Mob 　　：敵キャラクターの動きに関するクラス  
ゴール　　：クリア時の処理  
ゲームオーバー：クリア失敗時の処理  
              →プレイヤーと敵が接触したら終わり（現時点は自己申告）  
              →時間切れで終わり  
              →範囲外にキャラクターが出て終わり  
