# opennlp-chinese-models
opennlp中文训练模型分享

## cn-name.bin	通过中文人名识别性别模型
```
DoccatModel doccatModel = new DoccatModel(new FileInputStream("cn-name.bin"));
 DocumentCategorizerME   documentCategorizerME = new DocumentCategorizerME(doccatModel);
 double[] categorize = documentCategorizerME.categorize(new String[]{"郑","明","海"});
```

# 联系方式QQ:1020680508(请注明来自"opennlp-chinese-models")
