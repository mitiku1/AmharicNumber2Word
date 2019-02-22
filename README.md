# Amharic Number to Word
<p>
Converters Numbers from decimal representation to Amharic language word representation. The package supports numbers to 999,999,999,999,999. This are the numbers that could often comeup in real world. 
</p>

### Usage
This package provides one class(`am_num2word.Number2WordsConverter`) to handle number to words conversion.
```python
import am_num2word

number = 45232945075
converter = am_num2word.Number2WordsConverter(number)
print(converter.to_words()) # አርባ አምስት ቢሊዮን ሁለት መቶ ሰላሳ ሁለት ሚሊዮን ዘጠኝ መቶ አርባ አምስት ሺህ ሰባ አምስት
print(converter.coma_separated # 45,232,945,075'
```

### How to install
```console
pip install am-num2word
```

### Lincense
