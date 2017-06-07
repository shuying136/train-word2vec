# train-word2vec
训练中文需要：
- import codecs
- f = codecs.open(filename,'r','utf-8') 
- data = f.readlines()
- f.close()
- for line in data:
- print(line)
  
- 解码与编码
- u = '中文'
- g = u.encode('gbk')
- print(g.decode('gbk').encode('utf-8'))
