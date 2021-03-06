Mona font TTF version 2.90 (shinonome-0.9.9)
$Id: README-ttf.txt,v 1.7 2003/09/10 02:54:11 s42335 Exp $

NOTE: This document might be obsolete. 
      The latest information is on the web.
      See http://monafont.sourceforge.net/

注意: このドキュメントの情報は最新ではないかもしれません。
      最新の情報は、モナーフォントのホームページ
      ( http://monafont.sourceforge.net/ ) をご覧ください。


  Mona fonts (モナーフォント) は 2ちゃんねるの
  アスキーアート (以下 AA) を Windows 以外の環境で
  見るために作られたフリーのフォントです。

  2ちゃんねるの AA はその多くが MS P ゴシック 12pt を
  想定してつくられており、それ以外のフォントを使ったブラウザで
  見るとずれてしまいます。モナーフォントはフリーで配布されている
  東雲 (しののめ) フォントを改造し、文字幅を MS P ゴシックに
  合わせたもので、これを使うと Windows ユーザ向けに作られた AA を
  正しく見ることができます。文字幅以外にも、 AA のイメージがなるべく
  変わらないよう、作者の独断と偏見による変更を加えています。

  注意: このファイルはおもに MacOSX, Windows 上で使う方のため TTF版用です。
        UNIX用の BDF版については README.euc をご覧ください。  


-- 動作条件・インストール方法

  Mac OS X をお使いの方:
    Cocoa アプリ上でのみ使用可能です。
    Carbon アプリ上では正しく表示されませんのでご注意ください。
    インストールは普通に「フォント」フォルダに入れてください。

  Windows NT/2000/XP をお使いの方:
    インストールは普通に「Fonts」フォルダに入れてください。

  Windows 95/98/Me をお使いの方:
    インストールは普通に「Fonts」フォルダに入れてください。


-- 注意

  ・ 多くの AA は、16ポイント (Windows では 12ポイント) の
     モナーフォントを使ったときに最もズレが少なく表示されます。

  ・ Unicode 特有の文字はほとんど含まれていません。そのため、
     これらを使っている一部の AA では文字が欠けたりズレが生じます。

  ・ MacOS で、Unicode 文字列を表示するようなアプリケーション
     (Finder など) ではモナーフォントを使わないでください。
     モナーフォントには Unicode 特有の文字が含まれていないため、
     表示がおかしくなることがあります。

  ・ ほとんどの Carbon アプリケーションでは字幅が固定になったり、
     半角文字が正しく表示されないという現象が発生します。


-- 変更履歴

  Sep. 9, 2003
	version 2.90
	アウトラインも AA に対応。
	Unicode 用のビットマップフォント (-mona-gothic-*-iso10646-1) で、
	バックスラッシュが￥になっていた問題を解決。

  Aug. 5, 2003
	version 2.30-pre2 ふたたび公開。
	アウトラインを kochi-substitute にした。
	ttfpack の効率化 (by 18さん)。
	グリフの追加 (by Hideki Ikemoto さん)。

  Jun. 18, 2003
        東風フォントの問題により、アウトライン版の配布 (2.30pre) を停止。

  Jan. 11, 2003
	version 2.30-pre
	東風ゴシックを埋めこみ。
	グリフの修正 (チルダ文字)。
	ttfpack の効率化 (by 18さん)。
	spec の修正。

  Dec. 20, 2002
	version 2.22
	全サイズで ISO-10646 (Unicode) に対応。
	16ポイントの英数字グリフを修正。
	make_cmap, ttfpack の効率化 (by 18さん)。

  Jun. 22, 2002
	version 2.21
	Shinonome-0.9.8 (0.9.9) に同期。
	jis2unicode のバグ修正。
	AA がよりしっくりくる 638 さんのパッチ適用。
	18 さんのパッチにより Windows版を Cyrillic, Greek に対応。

  May. 14, 2002
	version 2.2
	16ポイントのみ ISO-10646 (Unicode) に対応する。
	(TrueType 版はまだ未対応)
	bdfmerge を新しくする。

  Mar. 28, 2002
	version 2.12
	16ポイントのMS拡張部分を修正 (by 18番の名無しさん)。

  Mar. 22, 2002
	version 2.11
	16ポイントのMS拡張部分を修正 (by 18番の名無しさん)。
	16ポイントの片仮名・平仮名グリフを微調整。
	Windows NT で使えない問題を修正 (by 18番の名無しさん)。

  Feb. 14, 2002
	version 2.1 正式リリース。
	Carbon 対応は諦める。

  Feb. 9, 2002
	version-2.1beta-20020209
	cmap を修正 (スクリプトのバグにより一部間違ったパラメータ混入)。
	shinonome-0.9.7 に対応。

  Feb. 6, 2002
	version-2.1beta-20020205
	cmap を修正。hdmx を追加。
	Win98 系ではほぼ使えるレベルになった。

  Feb. 4, 2002
	version-2.1beta-20020204
	name, cmap, EBSC を修正。
	まだ NT 系ではダメだと思う。MacOSXでは文字化けするそうな。

  Jan. 17, 2002
	version-2.1beta-20020117
	ttf 版はつおひろめ。テストは Win98 上のみ。
	NT, 2000, MacOSX では動かないらしい。

  ...
  Feb. 10, 2001
	モナーフォント X11 版の最初のリリース。


-- ライセンスおよび配布条件

  モナーフォントは無保証です。
  モナーフォントのライセンスは東雲フォントのライセンスに準じます。
  東雲フォント自体は実質的な public domain となっているため、
  モナーフォントもこれにならいます。
  このアーカイブ中に含まれるフォントおよびツール類の改変、再配布、雑誌や
  CD-ROM 等への掲載はご自由にどうぞ。作者への連絡等は不要です。

(以下は東雲フォントのアーカイブに含まれている LICENSE ファイルの内容です)
--------------------------------------------------------------
●東雲フォントライセンス
                                                                    2001
                                     The Electronic Font Open Laboratory
                                        http://openlab.ring.gr.jp/efont/

このアーカイブに含まれるすべてのフォントデータ、ドキュメント、スクリプ
ト類はすべて Public Domain で提供されています 。

但し、日本に於いては現時点で著作権を放棄することは法律上不可能であり、
AUTHORS に列挙されている作者がその権利を行使しないと宣言することで実質
的な Public Domain であるとします。

自由な改造、他フォーマットへの変換、組込み、再配布を行うことができます。
同時に、これらはすべて完全に無保証です。
--------------------------------------------------------------


-- TODO

  ・ アウトラインの調整。
  ・ ISO-10646 (Unicode) 版の整備。
  ・ NT で Windows 外字の漢字が見えません。
     Unicode からのマッピングが定義されていない (例えば U+FAxx の
     あたりとか) からではないかと思います (by 18番の名無しさん)。
  ・ その他微調整。
  ・ maxp, hhea, head の最大・最小値調整。


-- 謝辞

  以下の方々に感謝します:

  古川 泰之さん (東雲フォント, mkbold, mkitalic)
  /efont/ プロジェクトの方々
  NAGAO Sadakazu さん (mkbold)
  Toshiyuki Imamura さん, HANATAKA Shinya さん ({K12,K14,jiskan16}-2000)
  小田嶋勝也 さん (a16rk)
  狩野 宏樹さん (bit2bdf)
  18番の名無しさん (omaemona, oremona, monak14-ext, その他いろいろfix)
  Yukihiro Nakai さん (RedHat用 RPM spec)
  Macintosh版、NT版のテストに協力してくれた方々
  2ちゃんねるでいつも相手をしてくれる方々 & 神技 AA職人の方々


-- 作者からのおねがい

  フォントの形状はまだ改善の余地があると思っています。
  「この文字のこの部分は気に入らない。こう変えたらどうか?」という提案は
  どんどんしてください。文字のビットマップを送っていただければ対応します。
  bit ファイルの context diff 形式が ベストですが、それ以外の
  形式でもかまいません。
  小さいものなら 2ch のスレッドに sage で貼りつけるのもありかと。


-- 作者について

  Monafont 公式ページ: http://monafont.sourceforge.net/
  モナーフォントスレッド(2ch UNIX板): http://pc.2ch.net/test/read.cgi/unix/1043510520/l50

  インストールや使い方に関する質問・ご意見は 2ちゃんねるスレッドで
  お願いします。
