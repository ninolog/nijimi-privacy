# Nijimi プライバシーポリシー

最終更新日：2026年10月1日

Nijimi（以下「本拡張機能」）は、YouTube・Twitch・X で表示している動画や画像の色を、ページの周りに光として映す Chrome 拡張機能です。本拡張機能は、利用者の個人情報を収集・送信・販売しません。

## 収集する情報

本拡張機能は、利用者に関する情報を一切収集しません。アクセス解析、広告、外部サービスへのデータ送信も行いません。

## ページの内容の扱い

本拡張機能は、次のサイトでのみ動作します。

- https://www.youtube.com/
- https://www.twitch.tv/
- https://x.com/ ・ https://twitter.com/

これらのページで表示されている動画や画像を、光を描くためにブラウザの中で読み取ります。読み取った映像は光の表示にだけ使い、保存したり、外部に送信したりすることはありません。

動画がまだ読み込まれていないときは、光の色の元として、その動画のサムネイル画像を各サービスの画像サーバー（YouTube の i.ytimg.com、Twitch の static-cdn.jtvnw.net）から読み込むことがあります。これはページ自体が画像を表示するときと同じ通常の読み込みで、本拡張機能から何らかの情報を送るものではありません。

## 端末に保存する情報

本拡張機能は、Chrome の拡張機能用ストレージ（chrome.storage.local）に次の情報を保存します。保存先は利用者の端末の中だけで、外部には送信されません。

- 設定値（オン・オフ、ぼかし、広がり、明るさなど）
- YouTube ショートの表示を整えるための、ページ部品の目印（要素の名前やクラス名）

これらの情報は、本拡張機能をアンインストールすると削除されます。

## 権限について

- `storage`：上記の設定値と目印を保存するために使います。
- 対象サイトへのアクセス（上記4つのアドレス）：そのページの動画や画像に光を付けるために使います。これ以外のサイトにはアクセスしません。

## 本ポリシーの変更

本ポリシーを変更する場合は、このページで更新内容と最終更新日をお知らせします。

## お問い合わせ

本ポリシーに関するお問い合わせは、このリポジトリの Issues（https://github.com/ninolog/nijimi-privacy/issues）からお願いします。

---

# Nijimi Privacy Policy

Last updated: October 1, 2026

Nijimi ("the extension") is a Chrome extension that casts the colors of the video or image you are watching on YouTube, Twitch and X around the page as light. The extension does not collect, transmit or sell any personal information.

## Information we collect

None. The extension collects no information about you. It has no analytics, no ads, and sends no data to any outside service.

## How page content is used

The extension runs only on these sites:

- https://www.youtube.com/
- https://www.twitch.tv/
- https://x.com/ and https://twitter.com/

On those pages it reads the video or image being shown, inside your browser, to draw the light. What it reads is used only for that display; it is never stored or sent anywhere.

While a video has not loaded yet, the extension may load that video's thumbnail from the service's own image server (YouTube's i.ytimg.com, Twitch's static-cdn.jtvnw.net) to take the light's colors from. This is an ordinary image load, the same as the page's own; the extension sends no information with it.

## Information stored on your device

The extension keeps the following in Chrome's extension storage (chrome.storage.local), on your device only, never sent anywhere:

- Your settings (on/off, blur, spread, brightness and so on)
- Hints for laying out YouTube Shorts (names and class names of page elements)

They are removed when you uninstall the extension.

## Permissions

- `storage`: to keep the settings and hints above.
- Access to the sites listed above: to add the light to the video or image on those pages. The extension does not access any other site.

## Changes to this policy

If this policy changes, the update and its date will be posted on this page.

## Contact

For questions about this policy, please open an issue on this repository: https://github.com/ninolog/nijimi-privacy/issues
