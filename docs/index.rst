.. You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

BIG-IP Local Traffic Manager (LTM) v17.5 簡単セットアップガイド
==============================================
最終更新日: 2025年4月11日


はじめに
--------------------------------
このページでは、これらのオフィシャルなドキュメントの補足となる資料 や 複数の機能を組合せてソリューションを実現する方法をご紹介いたします。
F5のオフィシャルなドキュメントはこちらにございます。

- AskF5: https://support.f5.com/csp/home
- F5 Cloud Docs: https://clouddocs.f5.com/
- F5 DevCentral（コミュニティ）: https://devcentral.f5.com/


その他参考リンク
--------------------------------

- F5 テクニカルインフォTop : https://f5j-tech-info.readthedocs.io/
- F5 Japan YouTube : https://www.youtube.com/channel/UCqX6rJEY6Ya8YbC8iqP34zg
- F5 NGINX YouTube(英語) : https://www.youtube.com/@nginx_official



コンテンツ
--------------------------------
このページでは、以下の内容をご紹介しております。


- 本セットアップガイドにて、BIG-IP Local Traffic Manager (以下"LTM")の設定方法についてご案内します。
- BIG-IP LTMはサーバ負荷分散をはじめとして、SSLオフロードやコンテンツスイッチング、また圧縮やキャッシュなど多彩な機能を搭載し、アプリケーションサービス䛾可用性を高め、快適なユーザエクスペリエンスを提供するのに役立ちます。
- 本ガイドでは、BIG-IP LTMをご購入いただいてすぐに使い始められるように、サーバ負荷分散を実現するのに必要となる典型的なセットアップ手法を、スクリーンショットを交えて紹介します。
- これにより、ネットワークを構成し、クライアント－サーバ間で簡単なWebの負荷分散環境を構築することができますので、セットアップ時の手引きとしてご活用ください。
- 管理用のマネージメントIPアドレスは、設定済みである前提としております。
- 本ガイドは、F5 Japanにおけるハンズオントレーニングのコースでも利用しております。

.. note::
   本ドキュメントの手順は、F5 UDF (Universal Demonstration Framework)というラボ環境での実施を前提に書かれています。
   UDF以外での環境で利用される場合は、IPアドレス等は環境に合わせて読み替えてください。

.. toctree::
   :numbered:
   :titlesonly:
   :caption: 目次:
   :glob:

   content*/content*
