# project_web-version1

<h3>[功能進度]</h3>
<h4><b>已完成</b></h4>
抓取財政部網頁資料<br>
依選擇期別顯示中獎號碼<br>
可於文字方塊輸入號碼進行對獎<br>
顯示對獎結果<br>
登入/註冊<br>
儲存會員的發票號碼<br>
查詢會員的發票號碼<br>
<h4><b>未完成</b></h4>
對獎結果增加換頁功能-尚未進行<br>
<hr>
<h3>[PHP功能]</h3>
儲存獎別設定-prizeItems.php<br>
儲存獎金設定-prizeMoney.php<br>
取得獎金設定-getPrizeMoney.php<br>
儲存資料庫設定-config.php<br>
抓取網頁資料並寫入資料庫-catchWeb.php<br>
設定首頁可選擇期別-setDate.php<br>
搜尋資料庫中的中獎號碼-getWinNumber.php<br>
將搜尋出的中獎號碼傳入首頁-setWinNumber.php<br>
搜尋資料庫中的兌獎期限並傳入首頁-setWinPeriod.php<br>
上傳檔案並傳入首頁的文字方塊-uploadNumberFile.php<br>
將註冊資料寫入資料庫-signUp.php<br>
進行登入確認-signIn.php<br>
確認是否已登入-checkMember.php<br>
比對發票號碼-checkNumber.php<br>
呼叫checkNumber.php將結果以json格式回傳-setCheckNumber.php<br>
儲存會員發票號碼-addMemberNumber.php<br>
搜尋資料庫中的會員發票號碼-getMemberNumber.php<br>
將搜尋出的會員發票號碼傳入會員頁--setMemberNumber.php<br>
檢查帳密取得會員Email-getMemberEmail.php<br>