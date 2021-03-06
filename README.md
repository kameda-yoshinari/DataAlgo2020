# Data structure and Algorithm 2020
Data structure and Algorithm in 2020 at ESYS on U-Tsukuba, Japan.

**2021年度以降については，DataAlgo-UTのほうに展開します．**  
https://github.com/kameda-yoshinari/DataAlgo-UT

---

筑波大学工学システム学類3年生科目
データ構造とアルゴリズム(FG24711/FG34711) 担当：亀田能成

C言語で非数値データを扱ったりそれを処理するアルゴリズムについて勉強します．  
本github上で各colab notebookの図が表示されていなかったり，htmlマークアップが崩れていたりすることがあるかもしれませんが，これはcolabでの表示を想定しているからです．（同じjupyter notebookでもgoogle colaboratoryとgithubでは全く同じようにレンダリングしてくれるわけではない）  
（githubは画像の直接埋め込みに未対応の模様）  
ファイル末尾に"ext"がついているのは図を外部リンク(github上に展開)してます．ついていない場合は図をインライン展開しています（＝github上では図は表示されない)．
"Open in Colab" アイコンで Google Colaboratory に行って開けば，私が想定していた形ですべて閲覧できるはずです．  

【講義資料】  
003 ... 3.節に関連する演習実施のための準備  
3.節 グラフの探索  
--- ... 3.1.節 幅優先探索と深さ優先探索  
004 ... 3.2.節 幅優先探索  
005 ... 3.3.節 深さ優先探索  
006 ... 3.4.節 トポロジカルソーティング  
4.節 経路問題  
007 ... 4.1.節 最長経路問題  
008 ... 4.2.節 1対N最短経路問題(Dijkstra) ;  extあり
009 ... 4.3.節 N対N最短経路問題(Floyd) ; extあり
...

【課題】  
R03 ... 第3週課題の雛形    
R04 ... 第4週課題の雛形  
R05 ... 第5週課題の雛形
R06 ... 第6週課題の雛形
...

2020年度はCovid19のおかげで計算機室が利用不能になったこともあり，いっそのこと，というのでGoogle Colaboratoryベースに切り替えることにしました．
Google Colaboratoryという未来志向の環境を使ってわざわざC言語の授業資料公開しているのは私ぐらいかも‥
EclipseとかVisualStudioとか別のクラウドとかも考えた・調査したのですが，全学生に提供可能で，場所も問わずに，無料，となるとこれぐらいしか選択肢がないと思います．（あと大学院でもG-Colab使うのでそっちとの相乗効果で手間削減したかったというのもあったり）

【注意書】
githubで稀に「Sorry, something went wrong. Reload?」と言われることがあるかもしれません。
時間を空けて再度Reloadしても状況が改善しない場合は、少し手間ですが、
https://nbviewer.jupyter.org/
にアクセスし、当該リンクを張り付けて可視化（レンダリング）してみてください。  
（参考） https://stackoverflow.com/questions/62878732/how-to-display-a-ipynb-file-on-github

