・手数料・送料・クーポン利用など製品以外は一明細にはせず、カラム追加
・明細番号　追加
・クーポン＞＞コード・名称・値引額のカラム追加
・値引＞＞「値引計」に名称変更（クーポン値引＋ポイント値引）　*現状と変わらず
・合計と支払合計が同じ値が入っているので、
    合計＝（値引き前の合計）＝小計+手数料+送料
    支払合計＝（値引き後の合計）＝合計-値引
 ・発送日＞＞「出荷日」に名称変更。管理画面の名称と合わせる
 ・更新日のカラム追加
 ・ダブりの項目削除（注文番号・送料）
             
             
             
 - [] dtb_order.charge, dtb_order.delivery_fee_total
 - count(dtb_order_item)
 - plg_coupon_order.order_id, plg_coupon_order.coupon_cd, plg_coupon_order.coupon_name, plg_coupon_order.discount
 - [x] 値引＞＞「値引計
 - [] 値引き前の合計 = 合計 = dtb_order.sutotal + charge + delivery_fee_total 
 - [x] 発送日＞＞「出荷日」
 - [x] 更新日のカラム追加
 - [x] 項目削除（注文番号・送料）

 - 適当にテストできるところ
 - お客さんも店舗触ってる？
 - 危ないことありますか？
 - どうやってテストできる？

## tencent
 - tencent化粧品資格あるか
 - 10000人10000yen

## mini program
 - cutomize 90000 rmb
 - chinese 3800 rmb
 - customer service ????
 - 
 
## company
### 
 - name
 - what industry
 - id card
 - 2400/m
 - 1200/m

### 子会社
 - 本人行く
