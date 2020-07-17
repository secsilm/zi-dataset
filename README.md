# zi

汉字数据集，包括约 20000 个汉字的相关信息，具体字段包括：

| 字段                    | 说明                                                         | 举例                 |
|-------------------------|--------------------------------------------------------------|----------------------|
| `zi`                      | 汉字本身                                                     | 李                   |
| `stroke_count`            | 笔画数                                                       | 7画                  |
| `stroke_count_decomposed` | 笔画数拆解                                                   | 木 + 3               |
| `mandarin_pinyin`         | 普通话拼音                                                   | lǐ                   |
| `cantonese_pinyin`        | 粤语拼音                                                     | lei5                 |
| `english`                 | 英文                                                         | plum; judge; surname |
| `radical`                 | 部首                                                         | 木                   |
| `radical_stroke_count`    | 部首笔画数                                                   | 4                    |
| `radical_pinyin`          | 部首拼音                                                     | mù                   |
| `radical_english`         | 部首英文                                                     | tree                 |
| `variant`                 | 变体，通常为对应繁体                                         | NaN                  |
| `fc_code`                 | 四角码                                                       | 4040.7               |
| `cj_code`                 | 仓颉码                                                       | DND                  |
| `zis_with_this_component` | 包含该字的字，即以该字为部件的字，以英文逗号分隔，不包含本身 | NaN                  |
| `leaf_component`          | 叶子部件，即将该字拆分构成一个树后，其叶子节点便是叶子部件，用 `/` 拼接 | 木/子                  |

## WIP

- [ ] 添加笔画顺序
