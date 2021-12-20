## Behinder for M1

> 基于 [Behinder_v3.0 Beta 9 fixed](https://github.com/rebeyond/Behinder/releases/tag/Behinder_v3.0_Beta_9_fixed) 修改而来。

Behinder 无法在 M1 下运行的原因是 M1 仅支持 3.32.3.3 版本的 SQLite，所以替换掉原来 jar 包中的 SQLite 为 3.32.3.3 版本的即可。

SQLite 3.32.3.3: https://repo1.maven.org/maven2/org/xerial/sqlite-jdbc/3.32.3.3/sqlite-jdbc-3.32.3.3.jar

JavaFX: https://download2.gluonhq.com/openjfx/11.0.2/openjfx-11.0.2_osx-x64_bin-sdk.zip

运行

```bash
java --module-path ./lib --add-modules=javafx.controls --add-modules=javafx.fxml --add-modules=javafx.base --add-modules=javafx.graphics --add-modules=javafx.web -jar ./Behinder.jar
```



