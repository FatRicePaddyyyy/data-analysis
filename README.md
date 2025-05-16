# データ分析
- Kaggleなどのデータを用いてデータ分析をします。
- python 3.11 を使用しています。
- [こちら](https://www.kaggle.com/competitions/spaceship-titanic/data)からデータをダウンロードし、```宇宙版タイタニック/train.csv```に配置します。
- ↑↑のデータは再配布が問題ないライセンスなので、このリポジトリ上にも配置しています。
### 宇宙版タイタニック
LightGBMというモデルを変更するなく、特徴量エンジニアリングとアンサンブル学習によってモデルの精度を向上させていきます。


1. 1_EDAipynb.ipynb : EDAをします<br>
2. 2_normal.ipynb : とくに工夫をしないLightGBMです<br>
3. 3_欠損値.ipynb : 欠損値を中央値や最頻値で埋めます<br>
4. 4_LightGBMによる欠損値.ipynb : LightGBMで欠損値を埋めます<br>
5. 5_特徴量追加.ipynb : 列から新しく特徴量を作り出します<br>
6. 6_クロスバリデーション.ipynb : クロスバリデーションにより、同じモデルで複数回学習させることで精度を上げます<br>
7. 7_結果の解釈:SHAP値.ipynb : SHAP値により、モデルを解釈します<br>
