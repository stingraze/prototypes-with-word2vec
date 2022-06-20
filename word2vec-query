#Parts of code taken from https://builtin.com/machine-learning/nlp-word2vec-python
from gensim.models import Word2Vec

my_string = "This is a sentence. This is another sentence."
my_list = my_string.split()
print (my_list)

#Initialize list, append each sentence to list.
lst = []
for i in my_list:
	lst.append(my_list)

print(lst)

sentences = [['I', 'like', 'fish'],
			 ['I', 'like', 'whales'],
			 ['I', 'don\'t', 'like', 'sharks']
			]

w2v = Word2Vec(sentences, min_count=1)
w2v_2 = Word2Vec(lst, min_count=1)

#print(w2v)

# access vector for one word
#list the vocabulary words
words = list(w2v.wv.index_to_key)
words2 = list(w2v_2.wv.index_to_key)

print(words)
print(words2)
#Send to Solr Query. Not implemented yet.
