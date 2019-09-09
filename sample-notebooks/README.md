# LC4RI: Literate Computing for Reproducible Infrastructure

*Literate Computing for Reproducible Infrastructure* is our project, which utilizes Jupyter Notebook in the operational engineering area. It seeks collaborative communication leading to share and improve operational workflows of researchers, educators, engineers, and other practitioners for reproducible computing.  Jupyter Notebook enables us to describe automated operations with complementary principles, which aim to **keep humans in the automated operational loop**. We pursue resilient, *human-centered automated operations* (機械化) that should not excessively rely on *no-ops automation* (自動化).

Notebooks are machine-reproducible, human-readable, and human-substitutable procedures, which improve efficiency and robustness of operations **without pushing aside humans from black-boxed automation**. Keeping our ability to learn and grow, we can foster a resilient engineering team by encouraging sharing operational knowledge and developing skillfulness.


## About This DEMO

このデモ環境ではJupyterのインタフェースを使って、運用作業の一例としてのログ分析や、我々のチームがLC4RIの実践のために開発している各種Extensionを使ってみるといった体験ができます。

なお、この環境ではNotebookを自由に作成、編集することができますが、Notebookに対する変更等は、 **保存されません** 。この環境は[Binder](https://mybinder.readthedocs.io/en/latest/)サービスの上でデプロイされており、一定時間が経過すると自動的に削除されます。編集したNotebookなどの情報は失われますのでご注意ください。

また、Sidestickies という Notebookに対して Sticky Note（付箋）を付与する機能では [Scrapbox](https://scrapbox.io/product/)サービスを利用しています。デモ環境の Sticky Note は参照のみで、編集できません。


> <span style='background-color:mistyrose;'> ** Please respect guidelines and policies [MyBinder.org](https://mybinder.readthedocs.io/en/latest/user-guidelines.html) and [Scrapbox.io](https://scrapbox.io/product/) ** </span>


<img src="./tree/images/openhouse-2019-demo.png" align="right" width="25%" />

<span style='background-color:mistyrose;'> 質問等、お問い合わせは、Facebookページ https://www.facebook.com/groups/792904597583420/ に参加申請ください！</span>

## Notebookの実行方法

このデモ環境では、Notebookという形式で、実際に自身で実行可能な運用作業の例が保存されています。

[00_デモ環境の利用方法](00_デモ環境の利用方法.ipynb)を参考に、実際に実行をしてみてください。


## Literate Computingの運用への適用例

運用への適用例の一つとして、ログを分析する手順を記述したNotebookを体感いただけます。

* [01_Literate_Computingの運用への適用例](01_Literate_Computingの運用への適用例.ipynb)


## NII謹製Literate Computing機能拡張
Jupyterはもともとデータ分析用途に開発されたツールであるため、インフラの運用に適用するためにいくつかの機能拡張を施しています。以下は、その内容をご紹介するNotebookです。

* [02_NII謹製_Jupyterの機能拡張について](02_NII謹製_Jupyterの機能拡張について.ipynb)


## Notebookを介したコミュニケーションについて

Jupyterで行った経験を効率的に共有するためにいくつかの機能拡張を施しています。以下は、その内容をご紹介するNotebookです。

* [03_Notebookを介したコミュニケーション](03_Notebookを介したコミュニケーション.ipynb)
