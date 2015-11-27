1. 請分辨並寫出以下程式碼的名稱：

  ```ruby 
  a = 1 
  @a = 2
  @@a = 5
  user = User.new
  user.name
  user.name = "Joe"
  ```
2. 什麼是 module? 請寫一段程式碼說明一個 class 要如何使用一個 module 裡面的 method?

3. 請說明 class 和 instance variable 之間的差別

4. 如果今天我為一個叫 User 的 class 產生一個新物件的方式是: 
  ```ruby
  User.new("Bob", "male", "Engineer")
  ```
請寫出 User class 的 initialize method

5. self 在 class 裡和在 method 裡分別是指向什麼

6. attr_accessor 的功能是什麼

7. 請說明 public 和 private method 之間的不同

8. Ruby 是如何確保一個 module 的 method 會被 include 它的 class 使用到？ (提示：method lookup)