# 請修改 config.php 內的
# $sshIP="clogin1.twnia.nchc.org.tw"; // or clogin2.twnia.nchc.org.tw , glogin1.twni // 台灣杉SSH IP
# $ftpIP="xdata1.twnia.nchc.org.tw"; // or xdata2.twnia.nchc.org.tw // 台灣杉FTP IP
# $user="c00cjz00"; //  台灣杉帳號
# $otpKey = ''; // 台灣杉otp key, 
# OTPKEY取得網址: https://iservice.nchc.org.tw/module_page.php?module=nchc_service#nchc_service/nchc_service.php?action=nchc_unix_account_edit
# 
# 執行 
# run_SSH.bat or run_WinSCP.bat 即可自動連線

# 備註
# $vbScript="yes"; //yes or no  此項功能當填寫no時候, 可mask輸入密碼
$waitFor30Seconds="no";  //yes or no 此項功能當填寫no時候, 將直接登入, 但不保證可順利登入



