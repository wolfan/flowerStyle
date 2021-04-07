# SIZE.
- fui: 7680px
  - tv-8k: 7680px (7680x4320)
  - tv-4k: 3840px (3840x2160)
  - tv-1080p: 1920px (1920x1080)
  - tv-720p: 1280px (1280x720)
- wid: 1418px
- web: 1008px
- pad: 800px
- mob/mobile/screen: 420px
- watch: 320px

## DIVIDER & BORDER.
- bd: 1px
  - divider

# FONT.
- h1: 40px/2.8rem
- h2: 36px/2.3rem
- h3: 30px/1.9rem
- h4: 26px/1.5rem
- h5: 20px/1.2rem
- ft: 16px/1rem
- lh: 18px/1.2rem
- small: 12px/.9rem
- lease: 8px/.5rem

## FONT-WEIGHT.
- weight: 500/bold
- focal: 700

## FONT-FAMILY.
- ff: `'face-family'!important`
  - sass: `'face-family'!default`

# COLOR.
- main: 主色
- aux: 辅助色
- com: 补充色
- gray: 灰度（重要指示色）
- lig: 淡化
- enh: 增强
- wek: 弱化
- agg: 加重

```
:root{
  --main: ;
  --aux: ;
  --com: ;
  --gray: ;
  --lig: ;
  --enh: ;
  --wek: ;
  --agg: ;
  --bg: ;
  --cl: ;
  --lk: ;
  --hover: ;
  --line: ;
}
```

## PROMPT.
- def/default: 无色
- pri/primary: $main
- suc/success: $green & $blue/成功
- dan/danger: $red/危险
- war/warning: $yellow/警告
- dis/disabled: $gray-lg/辅助
- ina/inactive: $gray-wk/失效
- inv/inverse: $dark/重点
- error: $red/错误
- info: 补充、信息

## ELEMENT TONE DISTRIBUTION.
- cl: font-color.
  - cl-aux: `<small> alink: $aux; acolor: $small, $least.`
- lk: link-color `<a> <button>`.
  - hover/focus: 
  - sel/active: 
- table: 
- bar: 
- bg: `$main`
- line: `<td> border and row.`

## NAME GROUP.
- red
- pink
- orange
- yellow
- green
- cyan
- blue
- purple
- indigo
- brown
- black
  - true-black
- white
  - true-white
- gray
  - gray-wk
  - gray-lg
  - gray-dk
- dark
  - dark-lg
  - dark-dk

## TONING THRESHOLD.
- weak: 18
- light: 12
- dark: 18

## GROUP(SCSS).
- xx_group: