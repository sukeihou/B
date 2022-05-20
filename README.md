# B
2022-05-20 10:17:44,851 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]同期機能スレッドの処理を開始します。
2022-05-20 10:17:44,851 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]DBインスタンスの作成を行います。
2022-05-20 10:17:44,851 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]サーバースレッドの作成を行います。
2022-05-20 10:17:44,851 INFO parent_server.py 【同期機能ブロック】[サーバースレッド(親)]同期機能スレッドの処理を開始します。
2022-05-20 10:17:44,851 INFO parent_server.py 【同期機能ブロック】[サーバースレッド(親)]サーバーの立ち上げを行います。
2022-05-20 10:17:44,851 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]クライアントクラスの作成を行います。
2022-05-20 10:17:44,851 INFO client.py 【同期機能ブロック】[クライアントクラス]初期化処理を行います。
2022-05-20 10:17:44,851 INFO parent_server.py 【同期機能ブロック】[サーバースレッド(親)]クライアントからの入力待ちです。
2022-05-20 10:17:44,852 INFO client.py 【同期機能ブロック】[クライアントクラス]対向PCのサーバーへ接続処理を行います。
2022-05-20 10:17:44,852 INFO client.py 【同期機能ブロック】[クライアントクラス]対向PCのサーバーへ接続処理 : SUCCESS
2022-05-20 10:17:44,852 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]対向PCとの接続を確認しました。
2022-05-20 10:17:44,852 INFO parent_synchronize_function.py 【同期制御ブロック】【親機】同期準備が完了しました。
2022-05-20 10:17:44,852 DEBUG que_mode_control_file.py notify_sync_ready()
Traceback (most recent call last):
  File "parent_synchronize_function.py", line 322, in <module>
    synchronize_thread(MODE, SOURCE_IP,
  File "parent_synchronize_function.py", line 164, in synchronize_thread
    notify_sync_ready()
  File "/home/n520/Documents/同期機能ブロック/que_mode_control_file.py", line 94, in notify_sync_ready
    return que_put( SET_SYNC_READY )
  File "/home/n520/Documents/同期機能ブロック/que_mode_control_file.py", line 320, in que_put
    from block_mode_control import MODE_CHECK, mode_status_check
  File "/home/n520/Documents/同期機能ブロック/block_mode_control.py", line 26, in <module>
    import block_function_control
  File "/home/n520/Documents/同期機能ブロック/block_function_control.py", line 13, in <module>
    import que_on_screen_file
  File "/home/n520/Documents/同期機能ブロック/que_on_screen_file.py", line 20, in <module>
    import  main
  File "/home/n520/Documents/同期機能ブロック/main.py", line 30, in <module>
    from que_on_screen_file import que_on_screen
ImportError: cannot import name 'que_on_screen' from partially initialized module 'que_on_screen_file' (most likely due to a circular import) (/home/n520/Documents/同期機能ブロック/que_on_screen_file.py)
n520@n520-XA7C-R38:~/Documents/同期機能ブロック$ python3 parent_synchronize_function.py
2022-05-20 10:19:14,798 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]同期機能スレッドの処理を開始します。
2022-05-20 10:19:14,798 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]DBインスタンスの作成を行います。
2022-05-20 10:19:14,798 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]サーバースレッドの作成を行います。
2022-05-20 10:19:14,798 INFO parent_server.py 【同期機能ブロック】[サーバースレッド(親)]同期機能スレッドの処理を開始します。
2022-05-20 10:19:14,798 INFO parent_server.py 【同期機能ブロック】[サーバースレッド(親)]サーバーの立ち上げを行います。
2022-05-20 10:19:14,799 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]クライアントクラスの作成を行います。
2022-05-20 10:19:14,799 INFO client.py 【同期機能ブロック】[クライアントクラス]初期化処理を行います。
2022-05-20 10:19:14,799 INFO client.py 【同期機能ブロック】[クライアントクラス]対向PCのサーバーへ接続処理を行います。
2022-05-20 10:19:14,799 INFO parent_server.py 【同期機能ブロック】[サーバースレッド(親)]クライアントからの入力待ちです。
2022-05-20 10:19:14,799 INFO client.py 【同期機能ブロック】[クライアントクラス]対向PCのサーバーへ接続処理 : SUCCESS
2022-05-20 10:19:14,799 INFO parent_synchronize_function.py 【同期機能ブロック】[親機]対向PCとの接続を確認しました。
2022-05-20 10:19:14,799 INFO parent_synchronize_function.py 【同期制御ブロック】【親機】同期準備が完了しました。
2022-05-20 10:19:14,799 DEBUG que_mode_control_file.py notify_sync_ready()
Traceback (most recent call last):
  File "parent_synchronize_function.py", line 322, in <module>
    synchronize_thread(MODE, SOURCE_IP,
  File "parent_synchronize_function.py", line 164, in synchronize_thread
    notify_sync_ready()
  File "/home/n520/Documents/同期機能ブロック/que_mode_control_file.py", line 94, in notify_sync_ready
    return que_put( SET_SYNC_READY )
  File "/home/n520/Documents/同期機能ブロック/que_mode_control_file.py", line 320, in que_put
    from block_mode_control import MODE_CHECK, mode_status_check
  File "/home/n520/Documents/同期機能ブロック/block_mode_control.py", line 26, in <module>
    import block_function_control
  File "/home/n520/Documents/同期機能ブロック/block_function_control.py", line 13, in <module>
    import que_on_screen_file
  File "/home/n520/Documents/同期機能ブロック/que_on_screen_file.py", line 20, in <module>
    import  main
  File "/home/n520/Documents/同期機能ブロック/main.py", line 30, in <module>
    from que_on_screen_file import que_on_screen
ImportError: cannot import name 'que_on_screen' from partially initialized module 'que_on_screen_file' (most likely due to a circular import) (/home/n520/Documents/同期機能ブロック/que_on_screen_file.py)
