# SpringBootのクラウドネイティブビルドを試す（Maven版）

### 使用ツール
- VSCode

### インストール
```
mvnw clean install
```

### イメージの作成
```
mvnw spring-boot:build-image
```

### 起動方法
```
docker run -it -p8080:8080 demo:latest
```

### 確認方法
- [ローカルホスト](http://localhost:8080)にアクセス