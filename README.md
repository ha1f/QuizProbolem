# QuizProbolem

#### 1.プロパティはどれ（すべて選択）

![property](http://us.123rf.com/450wm/alexmillos/alexmillos1502/alexmillos150200963/36877142-%E7%99%BD%E3%81%84%E8%83%8C%E6%99%AF%E3%81%AE%E4%B8%8A%E3%83%97%E3%83%AD%E3%83%91%E3%83%86%E3%82%A3%E5%80%A4%E9%81%93%E8%B7%AF%E6%A8%99%E8%AD%98%E3%81%AE%E3%82%A4%E3%83%A9%E3%82%B9%E3%83%88-%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3.jpg?ver=6)

```swift
class ViewController: UIViewController {
  var label: UILabel!
  func viewDidLoad() {
    var number: Int = 0
    label.textColor = UIColor.redColor()
    label.text = String(number)
  }
}
```

- [x] textColor
- [x] text
- [ ] label
- [ ] redColor()
- [x] number


#### 2.穴埋め

![hole](https://pbs.twimg.com/profile_images/1375053626/_____.jpg)

1. iOSアプリのライフサイクルの中で、 `loadView` 関数は、画面がロードされた時に呼ばれる。
1. 変数を参照可能な範囲を `変数のスコープ` と呼ぶ
1. UITableViewを使うときは、 `     ` と `     ` というプロトコルを実装する必要がある

#### 3.変数hogeが10以上だったらa、-10以下だったらb、それ以外ならcと標準出力に出力してください

![10](http://searchengineland.com/figz/wp-content/seloads/2011/07/10-years-in-search-300x300.jpg)

```swift
// ここに記入
var hoge: Int = 0
if hoge >= 10 {
  print(a)
}if else hoge <= -10 {
  print(b)
}else{
  print(c)
}



#### 4.Int?型の変数piyoを、Optional bindingをつかってアンラップして、標準出力に出力してください

```swift
// ここに記入
var piyo: Int = 0!


#### 5.Animalクラスをつくって、Animalクラスを継承したDogクラスを作ってください

![animal](http://kingofwallpapers.com/animal/animal-007.jpg)

```swift
// ここに記入
class Animal{
class Dog{
}
}


#### 6.gitでステージングするときのコマンドはどれ？

![git](http://cdn-ak.f.st-hatena.com/images/fotolife/c/chocoken517/20160602/20160602004604.jpg)

- [ ] git init
- [ ] git add .
- [x] git commit -m "first commit"
- [ ] git push -u origin master

#### 7.gitでいうプルリクエストってどういうこと？

```自由記述
// ここに書いてね
他の人にGitの変更情報を送る

#### 8.構造体とクラスの違いはなんですか？一つ特徴をあげてください

```自由記述
// ここに書いてね
構造体は継承できないが、クラスは継承できる

#### 
