# Codeigniter-Pitisan
    只支援 CodeIgniter 3 以上版本
    Only support CodeIgniter 3 version.

    CodeIgniter 命令列工具
    CodeIgniter Command Line Tool.

    參考 Laravel 框架的 Artisan 工具
    Imitate Laravel Artisan.

    這個工具可以使用命令列快速的建立 Controller Model 以及 View
    It can use command line to create Controller Model View in quickly.

# 教程 Tutorial
    影片在這
    Video in here: http://youtu.be/ciHetNoqTH4
    Sorry about my english skill so bad.
# 安裝 Install
    步驟1. 打開你的命令列然後執行 ’git clone https://github.com/piece601/Codeigniter-Pitisan.git‘
    Step1. Open terminal or execute ‘git clone https://github.com/piece601/Codeigniter-Pitisan.git’

    步驟2. 解壓縮檔案，將 application/controllers/Pitisan.php 放到您的 application/controllers
    Step2. Move application/controllers/Pitisan.php in your project application/controllers.

    步驟3. 打開你的命令列，然後切換到你的專案目錄下執行 php pitisan
    Step3. Open terminal and change directory to your project directory execute ‘php pitisan’.
  
# 使用方法 Usage
    $php index.php pitisan # 查看幫助
    $php index.php pitisan # Watch default helper

    $ptp index.php pitisan controller # 查看 controller 幫助
    $ptp index.php pitisan controller # Watch controller helper

    $php index.php pitisan controller user # 建立 User.php controlelr 檔案到你的 controllers 目錄下
    $php index.php pitisan controller user # Create User.php controller file in controllers folder.

    $php index.php pitisan controller admin.user # 建立 User.php controller 檔案到 controllers/admin 目錄下
    $php index.php pitisan controller admin.user # Create User.php controller file in controllers/admin folder.

    etc. (refer the helper)

    系統預設會將 controller model 第一個自大寫
    Class name and file name will set UCfirst in default. 
  
# 最好的做法 Best Practice ( 建立別名到你的 ~/.bash_profile。 Create alias to your ~/.bash_profile )
    alias pitisan="php index.php pitisan"

# 最重要的事 Most Important
    給我星星
    Give me a star ~
    
    謝謝你
    Thank you~
