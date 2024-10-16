# sentiment_words_arabic.py

مكتبة الكلمات الإيجابية والسلبية. العربية و اللهجة الجزائرية

## كيفية الاستخدام

```python
from sentiment_words_arabic.py import add_positive_word, remove_positive_word, count_sentiment_words

# إضافة كلمة إيجابية
add_positive_word('كلمة جديدة')

# حساب عدد الكلمات الإيجابية والسلبية في نص

text =" مليحة مقودة شابة مرنك"
print(count_sentiment_words(text)) #{'pos': (2, ['مليحة', 'شابة']), 'neg': (2, ['مقودة', 'مرنك'])}

print(len(positive_words)) #242
print(len(negative_words)) #164