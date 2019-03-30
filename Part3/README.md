Part3のNotebookは、Colaboratoryでも実行できます。以下リンクをクリックし、Colaboratoryを実行してください。

[Chapter7.1](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.1.ipynb)  
[Chapter7.2](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.2.ipynb)  
[Chapter7.3](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.3.ipynb)  
[Chapter7.4](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.4.ipynb)  
[Chapter7.6](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.6.ipynb)  
[Chapter7.7](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.7.ipynb)  
[Chapter7.8](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.8.ipynb)  
[Chapter7.9](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter7.9.ipynb)  
[Chapter8.1](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter8.1.ipynb)  
[Chapter8.2](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter8.2.ipynb)  
[Chapter8.3](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter8.3.ipynb)  
[Chapter8.4](https://colab.research.google.com/github/hayatoy/gcpml-book/blob/master/Part3/Chapter8.4.ipynb)  

### Colaboratoryから実行する場合、以下のステップが追加で必要となります。
**BigQueryやGCSにデータを読み書きする箇所は、アクセス権が必要となるため以下のステップが必要です**  
- 認証をするためのコードをセルに追加
  - メニューの[Insert] -> [Code cell]をクリック
  - 以下のコードをセルに入力
    ```
    from google.colab import auth
    auth.authenticate_user()
    ```
  - 実行すると認証のためのURLが生成されるので、クリックしてログインする
  - 表示されるコードを、セルの入力フィールドに入力してEnter
