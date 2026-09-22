# syan. デモサイト 制作メモ

## 参考サイト（2026-09-22に検索・公式サイトを開いて確認）
- https://www.pueblo-hair.com/ — FVはロゴ・外観・地域案内、電話が最も強い導線。主な流れはお知らせ→紹介→キッズ→料金→設備→営業・予約→地図の約7節。黄・白・黒、ゴシック中心。子連れ対応と駐車場を具体的に案内する型を採用し、色と情報密度はsyan.向けに変更。
- https://www.hair-sunrise.com/ — FVは外観写真と大きな電話番号。お知らせ→コンセプト→営業時間→カレンダー→SNSの約5節、メニュー・アクセスは別ページ。深緑・白、ロゴはセリフ、本文はゴシック。電話と休日案内の見つけやすさを採用し、本デモでは1ページに集約。
- https://slow-salon.com/ — FVは小さなロゴと写真領域、上部にWEB予約。紹介→料金→補足の約3節を基本とし、店舗情報等は別ページ。白・グレー・細いゴシック・広い余白。予約の直接リンクと余白を採用し、syan.では営業時間を冒頭へ追加。写真や文章は転用していない。

## 調査上の留保と構成
検索ではSUNRISEの好意的な接客・子連れ評価を確認（https://beauty.hotpepper.jp/slnH000213841/review/）。PUEBLOとSLOWは地域・子連れ対応・公式サイトの整備を優先した参考で、評判の十分な独立検証には至っていない。評価順位を意味しない。
来店客が探す情報は料金と施術時間、予約方法、営業日、場所と駐車場、担当者、店内の様子、子連れ利用条件。今回はヒーロー→案内リンク→お店と子連れ対応・ショップ→メニュー→予約→曜日別営業時間→アクセス→お問い合わせ。スタッフは未確認のため独立紹介を作らない。

## 素材
Pexelsの静物写真3点。全写真を目視確認し、人物・外観・実店舗の全景を使わず、全て画像上にイメージ写真表記を配置。各ファイル200KB未満。
- 6207525 / Skylar Kang：タオルと植物。https://www.pexels.com/photo/potted-green-ficus-arranged-with-stack-of-towels-6207525/
- 7697654 / RDNE Stock project：コーム・クリップ等。https://www.pexels.com/photo/hairdresser-equipment-on-table-7697654/
- 6692948 / Tara Winstead：木のおもちゃ。https://www.pexels.com/photo/wooden-toy-beside-the-white-wall-6692948/
取得形式：https://images.pexels.com/photos/<ID>/pexels-photo-<ID>.jpeg?auto=compress&cs=tinysrgb&w=1200&q=75

## 掲載確認
【要確認：ホットペッパー予約リンクの掲載可否】
【要確認：Instagramリンク先を個人アカウントのままでよいか・店名アカウントがあるか】
本文の要確認箇所の全件は CHECKLIST.md に記載。

## 地図
指定の店名検索 `https://www.google.com/maps?q=syan.%20シアン%20安曇野&output=embed` を使用。外部リンクは指定place_idを使用し、リンク先の店名・住所「穂高4312-2」・電話を実画面で照合した。埋め込みの最終表示検証結果は CHECKLIST.md に記載。

## 技術・公開
HTMLにCSSと必要最小限のメニュー開閉JSを内包。img/は相対パス、フォーム・解析・OGP画像なし。noindexとデモ表記を配置。ボタンは白文字のコントラストを確保するため、指定シアンを濃い #376875 に調整（対白 約6.1:1）。外部リンクは新規タブとnoopener noreferrer、電話には外部矢印なし。
AGENTS.mdの既定のCloudflare／非公開GitHub／フォームより、今回の明示指定（GitHub Pages・public・フォームなし）を優先。営業時間はユーザー提示のGoogleマップ掲載値を使用し、他媒体から置換しない。自動の「営業中」判定は祝日・不定休が不明のため行わない。
