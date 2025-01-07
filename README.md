# GAOKAO-Bench-Updates

GAOKAO-Bench-Updates将中国2023年及之后的高考选择题作为数据集,是对[GAOKAO-Bench](https://github.com/OpenLMLab/GAOKAO-Bench)(包含2010-2022年高考题)测评框架的补充.我们希望将GAOKAO-Bench打造成可持续的大模型测评框架,见证中文大语言模型的不断发展.

## 数据集

GAOKAO-Bench-Updates的具体数据格式可参见[GAOKAO-Bench](https://github.com/OpenLMLab/GAOKAO-Bench#json%E6%A0%BC%E5%BC%8F%E8%AF%B4%E6%98%8E).

## 评测

评测框架和GAOKAO-Bench相同,具体文件见下表:

| 文件名                      | 功能                       |
| --------------------------- | -------------------------- |
| /Bench/objective_bench      | 生成客观题(选择题)答案     |
| /Bench/bench_function       | 测试相关函数               |
| /Bench/2023_Obj_Prompt.json | 2023年客观题(选择题)Prompt |
| /Bench/2024_Obj_Prompt.json | 2024年客观题(选择题)Prompt |

具体测评方式可以参考[GAOKAO-Bench](https://github.com/OpenLMLab/GAOKAO-Bench#%E7%AE%80%E5%8D%95%E7%A4%BA%E4%BE%8B).
