![Chatbot-NLTK](https://socialify.git.ci/aryasoni98/Chatbot-NLTK/image?description=1&font=KoHo&language=1&owner=1&pattern=Circuit%20Board&theme=Dark)

## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt')
nltk.download('wordnet')
```
