株式会社LINKS 公式ホームページ 第4案
制作日：2026年10月20日

【構成・確認方法】
・index.htmlをブラウザで開くと閲覧できます。フォルダ全体を同じ構成のまま保存してください。
・HTML / CSSのみの静的サイトです。JavaScript、外部フォント、CDN、計測サービス、フォームは使用していません。
・画像とCSSはすべて相対パスです。ネット接続なしでも閲覧できます。
・ZIPの直下にindex.htmlと.nojekyllを格納しています。GitHub Pages向けの配置に対応しています。
・GitHubへのログイン、リポジトリ操作、Pages設定、外部公開は行っていません。
・iPhoneで確認する際は、展開したフォルダ全体を配信するローカル環境等から開いてください。ZIP内のHTMLだけをプレビューするとCSSや画像を参照できない場合があります。

【デザイン】
紙に近い淡い背景と深い紺色を基調に、全体ロゴと二つの業務イラストを配置しました。
PCでは内業と現場の誌面に段差をつけ、スマートフォンでは一列に並べて読み順を明確にしています。
大げさな宣伝文句や、常設の応募・問い合わせ導線は設けていません。
会社名、事業内容、業務内容、社員数は提供情報のみを使用しています。
イラストは業務を説明するイメージで、実在の社員・事務所・現場・所有車両を示すものではありません。

【ロゴ】
提供された「01_LINKS_全体_黒_白背景.svg」の全体ロゴだけを使用しました。
二つのパス（楕円と文字）の座標データが提供SVGと完全一致することを確認済みです。
変更は色、白背景の除去、周囲の余白（viewBox）の調整のみです。
文字だけ・楕円だけを単体表示する構成はありません。
紺版：assets/images/links-navy.svg
白系版：assets/images/links-ivory.svg

【表示確認】
・Microsoft Edge / Chromium：1440、1024、768、390、320px幅
・Playwright WebKit 26.5：390×844、375×667、430×932
・画面幅を超える横はみ出し、画像の欠落、リンク先の欠落、JavaScriptエラー、外部リクエストがないことを確認。
・会社概要リンク、先頭へ戻るリンク、JavaScript無効時、PCのfile://による直接表示を確認。
・PCとスマートフォン幅のスクリーンショットでレイアウトを確認。
・iPhone実機のSafariでは未確認です。WebKitでの確認は実機確認の代替を保証するものではありません。
・動く装飾は使用していません。ページ内移動はブラウザ標準のスクロールを使用し、動きを減らす設定に対応しています。

【ファイル一覧】
index.html
.nojekyll
README.txt
assets/css/style.css
assets/images/links-navy.svg
assets/images/links-ivory.svg
assets/images/office-work.webp
assets/images/field-work.webp

【イラスト制作記録】
OpenAIの組み込みimage_genツールを使用しました。初回生成後に画風を調整し、WebPへ軽量化しています。
保存先（このフォルダからの相対パス）：
assets/images/office-work.webp
assets/images/field-work.webp

初回・内業のプロンプト：
Use case: illustration-story. Asset type: illustration for the official informational website of a small Japanese telecommunications construction subcontractor. Create one beautifully composed semi-abstract, semi-realistic editorial company-brochure illustration. Sophisticated understated hand-drawn architectural rendering, accurate believable proportions and equipment, simplified human features, matte opaque gouache color planes with very fine graphite contour details, extremely restrained fine paper grain. Not photorealistic, not childish, not a generic flat vector cartoon, not glossy 3D. Quiet airy warm ivory background #f5f3ed, deep desaturated ink navy #223f50, blue-gray, stone gray, very small ochre accents. Soft diffuse light; calm competent everyday working mood, no heroic poses, no smiling at camera. Wide landscape 3:2 composition, all key subjects fully visible, balanced negative space around the outer edges, no border, no captions, no lettering, no logos, no watermark. Scene: a modest Japanese technical office, lightly suggested partial interior without a full rectangular room enclosure. View from slightly above at a natural three-quarter angle, not strict isometric. At left, one adult worker seated at a computer workstation, the screen shows a few faint schematic lines (no readable text); at center-right a wide uncluttered drafting desk with a large unfolded white technical drawing. Two adult colleagues in modest navy and gray work clothes review the drawing together; one stands and lightly points, one sits. Total three people. Faces small and discreet, gestures natural. Drawings are understated cable-route style lines, not intricate architectural floor plans. A few carefully placed folders and a pencil. Ensure natural hands and believable furniture. The drawing review and computer work must both be easily understood. No expansive luxury office, no plant decorations, no floating icons, no decorative abstractions.

初回・現場業務のプロンプト：
Use case: illustration-story. Asset type: illustration for the official informational website of a small Japanese telecommunications construction subcontractor. Create one beautifully composed semi-abstract, semi-realistic editorial company-brochure illustration. Sophisticated understated hand-drawn architectural rendering, accurate believable proportions and equipment, simplified human features, matte opaque gouache color planes with very fine graphite contour details, extremely restrained fine paper grain. Not photorealistic, not childish, not a generic flat vector cartoon, not glossy 3D. Quiet airy warm ivory background #f5f3ed, deep desaturated ink navy #223f50, blue-gray, stone gray, very small ochre accents. Soft diffuse light; calm competent everyday working mood, no heroic poses, no smiling at camera. Wide landscape 3:2 composition, all key subjects fully visible, balanced negative space around the outer edges, no border, no captions, no lettering, no logos, no watermark. Scene: routine maintenance on overhead telecommunications cable on a Japanese gray reinforced-concrete utility pole, in a quiet lightly suggested roadside environment. Main pole slightly right of center, cables extending naturally across upper part of the image. A modest white Japanese bucket truck with a navy accent is parked to the left of the pole; stabilizer legs visibly deployed. A coherent articulated hydraulic boom connects the truck to a bucket at communication-cable height. One worker with white safety helmet, gloves and safety harness inside the bucket doing cable inspection. One worker on ground wearing navy work clothes and white safety helmet looks up to check the work from a sensible safe position beside the truck. Total two workers. A couple of small muted ochre safety cones demarcate the working space. Accurate recognizable vehicle with believable wheels and cab; don't overemphasize mechanical detail. Only communication cables, no electrical transformers, no high-voltage equipment, no sparks. Simplified faint background low buildings and roadside boundary, no readable signs, no lush scenery. Pole top and boom and all wheels visible within frame. Show real work, with restrained simplified illustration detail.

最終・各生成画像に適用した画風調整プロンプト：
Use case: style-transfer. Change only the rendering style and background detail level of this illustration. Keep exactly the same work activities, meaningful equipment, positions, number of people, and broad landscape composition. Redraw as a quieter half-abstract editorial illustration with about 65% LESS detail. Clearly visible flat gouache shapes and thin sparse drawn contour lines, only two or three tones per object, minimal face marks (no realistic eyes/nose or individual hair strands), no realistic skin or clothing folds, no tiny texture. Warm ivory paper, muted ink navy, blue-gray, stone and a very small ochre accent. Remove peripheral clutter and most background interior/landscape detail, gently leaving broad ivory negative space behind the main work scene. The essential desk/PC/drawings or truck/boom/cables must stay immediately recognizable and mechanically coherent. The image should read as a drawn illustration at first glance, substantially more abstract than this reference, still adult and dignified. No photorealism, no anime, no cartoon exaggeration, no 3D, no words, labels, logos, watermark. Retain original 3:2 landscape aspect.

