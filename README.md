README.md  
  
# Ngano-cake  


## 説明

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
  
1. seed.rbにadminアカウント情報を以下のように追記。  
  
    Admin.create! {  
      email: "test@test"  
      password: "testtest"  
      }  
  
    ※passwordは8文字以上で入力。  
  
2. $ rails db:reset db:seed  
3. $ rails s  
4. adminログインページより設定したアカウント情報を入力してログイン。  

    url: （省略）～amazonaws.com/admins/sign_in  
  
## 開発環境  
amazon aws cloud9  
rails 5.2.4.4  

## ライセンス
MIT

## チーム & 開発者  
チームB_左右対称（dmm_webcampチーム開発)  
- なっちゃん  
- ゑびちゃん  
- ちばちゃん  
- まっさん  
