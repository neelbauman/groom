# GROOM

*Modus Operandi with ORG-mode*の*acronym*を逆から読んだもの。
「org-modeを使った仕事のやり方」,「org-mode運用法」といった意味となる。
groomの一般的な意味であるところの「手入れする」「きちんと整える」という意味とかけて、
org-modeを利用した仕事のマネジメントシステムを構築し運用することで、
consistentでよく手入れされた開発環境を成長させたいという思いから。

*groom* :: 
馬などを手入れする,きちんと身繕いする,未来に果たす役割または働きのために教育する,仕込む

*Modus Operandi* ::
仕事のやり方、運用法、物事の作用の仕方、犯罪の手口  

### Design Concept

##### 目標

1. consistentでwell-maintainedな作業環境を育てるためのタスク管理手法の策定
1. 1.の手法を実現するためのツールの設計/開発

org-modeのタスク管理機能の仕様からauthoringやtask managementについての
思想を抽出することができるだろう。
タスク管理が必要とされるあらゆる場面に組み込めて、
ストレスなくタスクマネジメントができる
ような手法にまで昇華させる。

##### 使用技術

+ Org Mode (emacs native)
+ git
+ shell script (bash)


<-- ##### What To Be ? -->


<-- ##### What Not To Be ? -->




### Org-modeについて

Org Modeは優れたツールだ。
なぜなら、それは単に機能を提供するだけでなく、そのspecificationを通じて
この世界をどのように取り扱うべきかをユーザーに教えてくれるから。

公式マニュアルのSummaryはOrgについての本質的な示唆に富んでいる。

> Org Mode is an authoring tool and a TODO lists manager for GNU Emacs. It relies on a lightweight plain-text markup language used in files with the ‘.org’ extension.

Orgは、authoring toolであると同時にtask managerである。

> As an authoring tool, Org helps you write structured documents and provides exporting facilities. Org files can also be used for literate programming and reproducible research.

> As a TODO lists manager, Org helps you organize your tasks in a flexible way, from daily needs to detailed project-planning, allowing logging, multiple views on your tasks, exporting your agendas, etc.

Orgは、authoring toolとして多くの形式に出力可能な構造化テキストファイルを書くことができる。
task managerとして、デイリーユースから詳細なプロジェクトプランニングまで
柔軟にオーガナイズし、記録し、多様な角度から集約し、また出力することができる。

> Org mode is implemented on top of Outline mode, which makes it possible to keep the content of large files well structured. Visibility cycling and structure editing help to work with the tree. Tables are easily created with a built-in table editor. Plain text URL-like links connect to websites, emails, Usenet messages, BBDB entries, and any files related to the projects.

Orgは、サイズの大きなファイルの構造化を効率的に取り扱うための仕組みを持っている。
また、website, email, Usenet messages, BBDB entries,その他プロジェクトに関連するファイルを
URL-likeなplain textで関連付けることもできる。


Orgは、テキストを書き、テキストをオーガナイズするためのいくつもの方法を可能にし、
そして、オーガナイズのための洗練された思想について教えてくれる。

例えばOrgは、どのようなカテゴリを作れば
一日の生活のなかで発生するイベントをミニマムでモレなくダブりなく分類しアイテム化できるか
について教えてくれる。

そしてイベントをどのように分類すべきについての観点まで教えてくれる。
さらには、各カテゴリの性質--つまり、
実行や状態の変化の記録はどのように残されるべきなのか、
TODOとしてリストされるべきなのか、
一日のスケジュールの中にどのように表示されるべきなのか、

Orgは、Visiblity cyclingとStructure editingを備えているので一つの大きなファイルを
優れた方法で取り扱うことができる。
また、AgendaやURL-like linksを備えているので、複数のファイルに分割されたファイルを
優れた方法で取り扱うこともできる。


