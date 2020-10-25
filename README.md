# AnueTestOther

1.VirtualBoxVM資料夾下有zip的分割檔，組起來的zip下會有兩個檔案，AnueTest.ova和帳號密碼.txt <br/>
  1_1.AnueTest.ova:VirtualBox VM匯出的備份檔案，該VM為Centos OS 7，並在上面安裝Docker建構MySQL資料庫和Redis緩存資料庫。 <br/>
  1_2.帳號密碼.txt:VM的帳號密碼和相關Docker安裝目錄資訊。

2.DBDDL資料夾下的DBDDL.txt有MySQL Schema和兩張Table Create的DDL sql

3.DockerRun下有兩個folder，MySQL和Redis <br/>
  3_1.MySQL資料夾下有一個docker-compose.yml檔案，VM內是用此docker-compose.yml來啟動MySQL Docker。 <br/>
  3_2.Redis資料夾下有兩個檔案DockerRun_Redis.txt和redis.conf，DockerRun_Redis.txt是VM內透過此Command去啟動Redis的Docker，<br/>
      redis.conf是啟動Redis Docker時候給Redis用的設定檔。
