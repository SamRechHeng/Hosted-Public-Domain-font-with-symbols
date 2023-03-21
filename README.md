# Hosted-Public-Domain-font-with-symbols
https://www.ctrl.blog/entry/creative-commons-unicode-fallback-font.html

![image](https://user-images.githubusercontent.com/127976898/226693705-a99fbda7-e256-42b2-8010-7fc904ccb9af.png)
### New font with Unicode-compatible Creative Commons license symbols
![image](https://user-images.githubusercontent.com/127976898/226693873-9145dd9d-9718-43b2-a66c-509f5364f977.png)

### Usage example

```
<style>
@import url("https://publicdomain-nocopyright.github.io/Hosted-Public-Domain-font-with-symbols/2020-04-19_cc-symbols/font-face.css");
@font-face {
  font-display: swap;
  font-family: CCSymbols;
  font-synthesis: none;
  src: url(CCSymbols.woff2) format(woff2),
       url(CCSymbols.woff)  format(woff);
  unicode-range: u+a9, u+229c,
                 u+1f10d-1f10f,
                 u+1f16d-1f16f;
}
</style>
<ccsymbol style="font-family: Helvetica,
               Arial,
               sans-serif,
               CCSymbols;">🅮</ccsymbol>

```
