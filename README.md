README.md  
  
# Ngano-cake  


## 説明
※DMM WebCampの課題です。  
長野県にある…のかもしれない、小さな洋菓子店「ながのCAKE」の商品を通販するためのECサイト。  
このアプリケーションを使うことにより、以下のサービスが受けられます。

- 注文に応じて製作する受注生産。  
- プレゼントとして、登録会員様以外のお届け先が設定可能。  
- お支払方法をクレジットカードや銀行振り込みに変更可能。  
etc...  

## 使い方
$ git clone https://github.com/sayutaisyou/nagano-cake.git  
$ cd nagano-cake  
$ bundle install  
$ rails s  

**以下adminとしてログインする方法**  
    
1. $ rails db:seed  
2. $ rails s  
3. 下記urlを参考にadminログインページより設定したアカウント情報を入力してログイン。  

    url: （省略）～amazonaws.com/admins/sign_in  
    
4. アカウント情報を以下のように入力してください。

    email : test@test  
    password : testtest
  
## 開発環境  
aws cloud9  
rails 5.2.4.4  

## ライセンス
MIT

## チーム & 開発者  
チームB_左右対称（dmm_webcampチーム開発)  
- なっちゃん  
- ゑびちゃん  
- ちばちゃん  
- まっさん  
