腳本直接取用了InDesign內置的FindChangeByList.jsx，獨立出來一是經常使用，二是為了避免衝突。

繁簡對照數據為OpenCC的[STCharacters.txt](https://github.com/BYVoid/OpenCC/blob/master/data/dictionary/STCharacters.txt)（2023-11-30）和[ChineseCharacters](https://github.com/lqfeng/ChineseCharacters)提取的台灣《[標準字與簡化字對照手冊](http://ws.moe.edu.tw/001/Upload/userfiles/%E6%A8%99%E6%BA%96%E5%AD%97%E5%B0%8D%E7%85%A7%E7%B0%A1%E5%8C%96%E5%AD%97.pdf)》

使用方式：
1. 把`繁to简.jsx`文件放入插件文件夾，如`/Applications/Adobe InDesign/Scripts/Scripts Panel/Samples/JavaScript/繁to简.jsx`
2. 把`繁to简.txt`文件放入同级的`FindChangeSupport`文件夾，如`/Applications/Adobe InDesign/Scripts/Scripts Panel/Samples/JavaScript/FindChangeSupport/繁to简.txt`
3. 在InDesign插件列表中運行該腳本。

目前共有3975條，電腦性能不同可能會卡頓一會兒。