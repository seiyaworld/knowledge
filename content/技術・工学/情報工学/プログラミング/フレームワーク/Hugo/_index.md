+++
#技術・工学 #情報工学 #プログラミング #フレームワーク #Hugo
title="Hugo"
description="This page gathers information about Hugo"
tags = ["技術・工学","情報工学","プログラミング","フレームワーク","Hugo"]
categories = ["技術・工学","情報工学","プログラミング"]
+++

Hugoに関するページ

### Hugo
このサイトはHugoで作成されています。  

#### テーマ(Relearn)
テーマは現在Relearnを使用しています。ドキュメント・Wiki用として適しています。  

##### インストール
gitで導入する場合  
```cmd
git init 
```

Git Submodule
```cmd
git submodule add --depth 1 https://github.com/McShelby/hugo-theme-relearn.git themes/hugo-theme-relearn
```

hugo.toml  
```hugotoml
theme = 'hugo-theme-relearn'
```

##### Taxonomies
tagsとcategoriesを実装  
``` hugotoml
[taxonomies]
	category = 'categories'
	tag = 'tags'
```

mdの方は以下ようにかく。  
```md
+++
tags = ["tag1","tag2","tag3"]
categories = ["category1","category2"]
+++
```

##### ShortCodes
[Expand](https://mcshelby.github.io/hugo-theme-relearn/shortcodes/expand/index.html)  
[Notice](https://mcshelby.github.io/hugo-theme-relearn/shortcodes/notice/index.html)  
