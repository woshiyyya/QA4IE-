# QA4IE-
QA4IE with noanswer and multi-answer cases

output: [
    data = {
        'q': ['question in word level', 'e.g. ["date", "of", "birth"]'], 
        'cq': ['question in character level', 'e.g. [["d", "a", "t", "e"], ["o", "f"], ["b", "i", "r", "t", "h"]]'], 
        'y': ['index of each answer word in context [sentence index, word index]', 'e.g. [[[0, 3], [0, 4], [0, 5]], ...]'], 
        '*x': ['index of context [article index, paragraph index]', 'e.g. [0, 0]'], 
        '*cx': ['same with *x'], 
        'ids': ['qa pair unique id', 'e.g. "fc24e824d79cb615408e88531909d39d"'],
        'answerss': ['answer string', 'e.g. ["15 May 1897"]'], 
        '*p': ['same with *x']
        },
    shared = {
        'x': ['context in word level', 'e.g. [["Five", "from", "the", "Jazz", "Band", ...]]'], 
        'cx': ['context in char level', 'e.g. [[["F", "i", "v", "e"], ...]]'], 
        'p': ['original context', 'e.g. "Five from the Jazz Band"'],
        'word_counter': 'word_counter', 
        'char_counter': 'char_counter', 
        'lower_word_counter': 'lower_word_counter',
        'word2vec': 'word2vec_dict', 
        'lower_word2vec': 'lower_word2vec_dict'
        }
    ]
