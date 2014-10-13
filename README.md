webdriver
=========

webdriverのテスト用のリポジトリ

TestSuiteにする場合
1.TestSuiteクラスを作成
2.以下を追加
@RunWith(Suite.class)
@SuiteClasses({
	Test1.class,　//任意のテストケースのクラス
	Test2.class,　//任意のテストケースのクラス
})

public class AllTests {　//テストスイートのクラス。中身はなくても良いっぽい。

}

これでTestSuiteを実行すれば出来るみたい。
eclipseでjuit4以降はウィザードで生成してくれないみたい。（最新のは未調査）
