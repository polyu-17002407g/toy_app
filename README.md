# README

* 2.2.1 演習
 1. 「User was successfully created.」がなくなりました。
 2. 新たなユーザーを作成できます。
 3. ユーザーを更新できます。
 4. 「Are you sure?」の「OK」をクリックすると、「User was successfully destroyed.」が表示されました。Railsはあのユーザーを削除(Delete)してから、全てのユーザーをデータベースから取り出しました(Select * from)。

* 2.2.2 演習
 1. ![/users/1/edit](/public/image/edit.png?raw=true)
 2. 
 ```
 def set_user
      @user = User.find(params[:id])
    end
 ```
 3. edit.html.erb