# robosyskadai1  
これは2021年度ロボットシステム学の講義の課題で作成したリポジトリです。
# 概要  
講義内で作成したプログラムを参考にして、自分自身の改良を加え、LEDを3個に増やして点灯、消灯をさせるプログラムを作成した。
# 動作環境  
・Raspberry Pi3  
・OS:ubuntu 18.04 LTS  
# 使用した部品
・LED3個  
・220Ω抵抗2個  
・ジャンパー線6本  
・ブレットボード1個   
# インストール&ビルド    
       
      $ make
      $ sudo insmod myled.ko
      $ sudo chmod 666 /dev/myled0  
# 実行方法  
・LED1を点灯、消灯させる  
       
      $ echo 1 > /dev/myled0
      $ echo 0 > /dev/myled0  
・LED2を点灯、消灯させる  
       
      $ echo 3 > /dev/myled0
      $ echo 2 > /dev/myled0  
・LED3を点灯、消灯させる  
       
      $ echo 5 > /dev/myled0
      $ echo 4 > /dev/myled0  
# 動画  
https://youtu.be/RbYR-4FwPWM  
# ライセンス  
https://github.com/Ryusei0923/robosyskadai1/blob/9520e6fafbf06cdb82e50ef6338b163bd2bcead3/COPYING
