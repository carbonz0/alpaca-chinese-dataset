# alpaca-chinese-dataset

alpaca中文指令微调数据集

## TODO
- 每份数据的生成方法待补充
- 清洗关键词及规则待补充

## 格式
- 与原始alpaca数据json格式相同

## 方法

### 数据生成
- 机器翻译
- self-instruct

### 数据清洗

### 样例

``` json
[
  {
      "instruction": "根据给定的坐标确定最近的机场。",
      "input": "40.728157, -73.794853",
      "output": "距给定坐标最近的机场是纽约市的拉瓜迪亚机场 (LGA)。"
  },
  {
     "instruction": "输出不同种类水果的列表",
      "input": "",
      "output": "1. 苹果\n2. 香蕉\n3. 橘子\n4. 芒果\n5. 草莓\n6. 葡萄\n7. 蓝莓\n8. 樱桃\n9. 猕猴桃\n10. 甜瓜\n11.菠萝\n12. 李子\n13.桃子"
  },
  {
     "instruction": "找出字串中隐藏的信息",
     "input": "业余咖啡",
     "output": "隐藏的消息是“咖啡因爱好者”。"
  }
 ]
```
