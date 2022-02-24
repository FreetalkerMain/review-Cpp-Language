# review-Cpp-Language
C++言語  のおさらい
  
## １，クラス使い方　基本
  
~~~cpp
#include <iostream>
using namespace std;

# クラスを定義する
class class1 {
public:
	char menberValue1;
} obj ;

#メイン関数から始まる
int main() {
	# class1型で作られたobjオブジェクトのmenberValue1メンバ変数を呼び出し、"string text"を代入する。
	obj.menberValue1 = "string text";
	
	# objオブジェクトのmenberValue1メンバー変数を呼び出し、coutに obj.menberValue1の内容を表示する（"string text"）
	cout << obj.menberValue1;

	return 0;
}

~~~


## ２，クラス　定義　基本(知ってるよ使いやすくなる。)
  
  
~~~cpp


~~~

## ３，クラス　定義発展　オーバーロード、オーバーライド
  
  
~~~cpp


~~~
