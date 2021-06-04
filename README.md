# Chunks-digger文本句法词块挖掘
dig out syntactic chunks from text

To run the codes, you need the Stanford CoreNLP(https://stanfordnlp.github.io/CoreNLP/) and NLTK(WWW.NLTK.ORG) installed.

运行环境需要: Stanford CoreNLP(https://stanfordnlp.github.io/CoreNLP/) 和 NLTK(WWW.NLTK.ORG)。

示例 example：

s="My name is Adam and I'm a freshman at senior high school."
SCdigText(s)

{"I'm a freshman at senior high school": (7, 'S'),
 "'m a freshman at senior high school": (7, 'VP'),
 'a freshman at senior high school': (6, 'NP'),
 'My name is Adam': (4, 'S'),
 'at senior high school': (4, 'PP'),
 'senior high school': (3, 'NP'),
 'My name': (2, 'NP'),
 'is Adam': (2, 'VP'),
 'a freshman': (2, 'NP'),
 'Adam': (1, 'NP'),
 'I': (1, 'NP')}
