缺少数据集，数据集下载链接http://data.gdeltproject.org/gkg/index.html
依据下载文件的日期去更改“文件整合.py”里面对应日期列表即可
后续文件整合以及数据预处理会自动生成对应的合并数据集combined_data.csv和经过处理的数据集preprocessed_data.csv。
文件预处理里面困惑度得分那段代码可以删去或注释掉，之前跑过了，最佳主题数是5。跑一次那段代码要五六个小时。
