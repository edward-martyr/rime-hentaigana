# rime-hentaigana: 一般の仮名と変体仮名の入力システム
 Input method of the complete set of kana, including hentaigana and other less used kana sets, like those in 台湾語仮名. 

## Installation

Installing Plum：

```bash
curl -fsSL https://git.io/rime-install | bash
```

Install  `rime-hentaigana` via Plum：

```bash
cd plum
bash rime-install edward-martyr/rime-hentaigana
```

Please check if the `opencc` folder is in the correct position if the kanji function of this input method is malfunctioning. 

## Functions

### Kana

- Input of modern kana
- Input of hentaigana
  - 𛀀, 𛀄, etc. 
- Input of 同じ marks
  - 〃, 々, ゝ, ゞ, 〴〵, etc. 
- 台湾語仮名
  - パ̣行 etc. 
- アイヌ語仮名
  - ㇱ, ㇲ, ㇳ, etc. 
  - ㇵ行
  - ㇻ行

### Kanji

In the menu you can switch from かな to 漢字 mode, which uses the `opencc` functionality to input kanji corresponding to hentaigana. 

## Tip

The dictionary is written using strictly phonological romanisation, e.g. using `sy-` for しゃ行, and `tu` for つ. 