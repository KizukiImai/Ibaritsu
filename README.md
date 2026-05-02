# いばりつ用テンプレ&スカウトシーン
いばりつで使う用のテンプレになるcontainerを含むtoeファイルです。

## 中身について

### シーケンスcontainer
<img width="912" height="713" alt="スクリーンショット 2026-05-02 194910" src="https://github.com/user-attachments/assets/323ca7ff-4d92-459e-88c6-75e00959ef20" />
後述するcontainerを含む物です。この中にあるものが上から順に実行されていきます。

### animationcontainer
<img width="650" height="527" alt="スクリーンショット 2026-05-02 194920" src="https://github.com/user-attachments/assets/9ca2448a-9337-4934-8e92-bd9ce6d3aab0" />
各シーンで最初に流れる動画を指定します。再生が終わると1を返します。物語の動画で説明する部分を格納する想定です。

### countdowoncontainer
<img width="666" height="562" alt="スクリーンショット 2026-05-02 194931" src="https://github.com/user-attachments/assets/d0f690b3-fe28-41c7-9990-41dddc03c9a6" />
各シーンで2番目に流れる動画を指定できます。体験コンテンツのルール説明や、カウントダウンを指定する想定です

### expcontainer
<img width="471" height="385" alt="スクリーンショット 2026-05-02 194943" src="https://github.com/user-attachments/assets/36108678-5ee5-4a4c-9e70-2756e286637a" />
各シーンのミニゲームを中に作るcontainerです。

### movieplayerと動画の指定方法
<img width="355" height="299" alt="スクリーンショット 2026-05-02 195403" src="https://github.com/user-attachments/assets/99da894f-ea75-4156-b17f-652f85c88ad8" />
animationとcountdownではこのmoivepayer containerを使って動画を再生しています。動画ファイルを選択した後、timerのlengthを動画の長さにしてください。
