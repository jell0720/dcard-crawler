# Dcard 爬蟲

學術用途。

爬取 Dcard 上的文章與留言做數據分析。

## 使用說明

1.  安裝 `ruby` (有的人可以跳過這個步驟)

    參考 <https://www.ruby-lang.org>

2.  安裝 `bundler` (有的人可以跳過這個步驟)

    ```bash
    $ gem install bundler
    ```

3.  安裝 `Postgres` (有的人可以跳過這個步驟)

    參考 <https://www.postgresql.org/download/>


4.  下載此專案

    ```bash
    $ git clone https://github.com/jk195417/dcard-crawler.git
    $ cd dcard-crawler
    ```

5.  安裝 `ruby` 外部函式庫

    ```bash
    $ bundle install
    ```

6.  執行

    ```bash
    # 執行主程式
    $ rake run

    # 執行命令列模式
    $ rake run:c
    ```
