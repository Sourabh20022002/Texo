# Texo

Under construction! Not ready for use yet! Currently experimenting and planning!

Developed by Sourabh Singh from Neuroins(c) 2023

## Examples of How To Use (Buggy Alpha Version)

Predicating Sentimental Analysis in English

```python
from Texo.Sentimental.Analysis import Sentitweeten

Analysis = Sentitweeten()
Out = Analysis.Tweet_analy('Analysis this Tweet')
print(out)
```

Predicating Sentimental Analysis in Hindi

```python
from Texo.Sentimental.Analysis import Sentitweeten

Analysis = Sentitweethn()
Out = Analysis.Tweet_anal('Analysis this Tweet')
print(out)
```

Find all stop_words from Text

```python
from Texo.Word.texo import tex
x = tex()
er = x.stop_words('This is a sample text with some stop words in it.')
print(er)
```


Find Summary from Text and number of Points of user Choice

```python
from Texo.Word.texo import tex
x = tex()
text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla at ligula diam. " \
       "Sed vel nibh ut purus sagittis tincidunt. Sed non lectus posuere, ullamcorper arcu nec, " \
       "elementum ipsum. Phasellus ut aliquam ligula. Duis sed tellus eget massa pulvinar " \
       "eleifend eu et augue. Nam pretium, tortor ac gravida malesuada, quam mauris tempor est, " \
       "et eleifend tortor mauris in dui. Vivamus ut pulvinar mauris, eget fermentum metus. " \
       "Cras nec varius ipsum. Sed sed neque vel ante vulputate gravida id a nisl. " \
       "Praesent facilisis imperdiet elit at rhoncus. Morbi ac scelerisque risus."

summary = x.summary(text, num_bullet_points=10)
print(summary)
```