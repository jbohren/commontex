Jonathan Bohren's Common TeX Stuff
==================================

### Usage

Clone:

```
git clone https://github.com/jbohren/commontex.git
ln -s commontex/sRGB_IEC61966-2-1_black_scaled.icc .
```

Add this to your preamble:

```
\usepackage{import}
\subimport{commontex/}{preamble}
```


