# opennlp-chinese-models
opennlp中文训练模型分享

## cn-name.bin	通过中文人名识别性别模型
```
DoccatModel doccatModel = new DoccatModel(new FileInputStream("cn-name.bin"));
 DocumentCategorizerME   documentCategorizerME = new DocumentCategorizerME(doccatModel);
 double[] categorize = documentCategorizerME.categorize(new String[]{"郑","明","海"});
```

## opennlp中文情感分类模型
测试结果：测试数据量11562 正确数9350 正确比例0.8086836187510811

数据来源 https://github.com/z17176/Chinese_conversation_sentiment

# 联系方式QQ:1020680508(请注明来自"opennlp-chinese-models")
