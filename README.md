# Archived(2023.03.02)

# Thanks
本项目由 [Typecho_WordsCounter](https://github.com/elatisy/Typecho_WordsCounter) 修改而来。
# WordsCounter
Typecho文章字数统计 & 全站字数统计插件
可在设置里调是否统计隐藏/私有文章字数

**注意:** 文件夹名字必须为**WordsCounter**才能正常使用

# Usage

## 文章字数统计
在你想要输出的地方加上
```php
<?php $this->charactersNum(); ?>
```

## 全站字数统计
在你想要输出的地方加上
```php
<?php echo WordsCounter_Plugin::allOfCharacters(); ?>
```
