
# A Simple Search Engine




## Acknowledgements

 - [The original project ](https://towardsdatascience.com/create-a-simple-search-engine-using-python-412587619ff5)
 - [ For understanding bs4 beautiful soup ](https://youtu.be/uufDGjTuq34)


## Features

- Gives an introduction to web scrapping 
- Tells about the ussage of AI in finding quality of the diffent words(TF-IDF)



## Roadmap

- Add the following libraries before starting with the code
    - lxml
    - requests
    - bs4(BeautifulSoup)
    - pandas( as pd)
    - numpy (as np)
    - sklearn
- This project has 3 steps
    - Creating a document
    - Create a Term-Document Matrix with TF-IDF weighting
    - Calculate the similarities between query and documents using Cosine Similarity and Retrieve the articles that have the highest similarity on it.


## Screenshots

### The class containg top links
![The class containg top links](https://miro.medium.com/max/1280/1*bGT4ejp_f_-7saaCtlWPCA.png)


### The class containing the information of the retrieved link

![The class containing the information of the retrieved link](https://miro.medium.com/max/1279/1*GJAP0mHFXc4JRG4Nn0gd6A.png)


## Tech Stack

**Client:** Visual Studio Code



## Example(Output)

PS C:\Users\nirma> & "C:/Program Files/Python310/python.exe" "c:/Users/nirma/Downloads/nitin search engine.py"
C:\Users\nirma\AppData\Roaming\Python\Python310\site-packages\sklearn\utils\deprecation.py:87: FutureWarning: Function get_feature_names is deprecated; get_feature_names is deprecated in 1.0 and will be removed in 1.2. Please use get_feature_names_out instead.
  warnings.warn(msg, category=FutureWarning)
                0         1         2         3         4    5         6    7        8         9
abaikan  0.000000  0.000000  0.000000  0.000000  0.000000  0.0  0.038897  0.0  0.00000  0.032509
absen    0.028371  0.000000  0.000000  0.000000  0.000000  0.0  0.000000  0.0  0.00000  0.000000
ac       0.000000  0.000000  0.000000  0.000000  0.029856  0.0  0.068060  0.0  0.00000  0.142208
achraf   0.028371  0.000000  0.000000  0.000000  0.000000  0.0  0.000000  0.0  0.00000  0.000000
ada      0.000000  0.092123  0.017086  0.053099  0.023838  0.0  0.000000  0.0  0.04708  0.000000
(1029, 10)
C:\Users\nirma\AppData\Roaming\Python\Python310\site-packages\sklearn\utils\deprecation.py:87: FutureWarning: Function get_feature_names is deprecated; get_feature_names is deprecated in 1.0 and will be removed in 1.2. Please use get_feature_names_out instead.
  warnings.warn(msg, category=FutureWarning)
Here:                          0         1         2         3         4    5         6    7        8         9
abaikan  0.000000  0.000000  0.000000  0.000000  0.000000  0.0  0.038897  0.0  0.00000  0.032509
absen    0.028371  0.000000  0.000000  0.000000  0.000000  0.0  0.000000  0.0  0.00000  0.000000
ac       0.000000  0.000000  0.000000  0.000000  0.029856  0.0  0.068060  0.0  0.00000  0.142208
achraf   0.028371  0.000000  0.000000  0.000000  0.000000  0.0  0.000000  0.0  0.00000  0.000000
ada      0.000000  0.092123  0.017086  0.053099  0.023838  0.0  0.000000  0.0  0.04708  0.000000

query: barcelona
the document with highest cosine probability:
similar documents: 0.03878394877816963
kompas com setiap gelaran piala dunia selalu ada pemain pemain muda yang tampil di perhelatan sepak bola terakbar empat tahunan itu namun di antara mereka cuma ada beberapa yang termuda siapa pemain termuda yang pernah bermain di piala dunia berikut adalah lima pemain termuda dalam sejarah piala dunia seperti dilansir dari laman theanalyst com baca juga tim yang juara piala dunia di negeri sendiri di urutan pertama ada nama norman whiteside eks pemain manchester united itu adalah pesepak bola termuda yang pernah bermain di piala dunia yakni pada edisi yang digelar di spanyol kala itu norman whiteside berlaga di piala dunia saat berumur tahun hari pemain termuda kedua dalam sejarah piala dunia ditorehkan oleh mantan striker barcelona dan timnas kamerun samuel eto o samuel eto o masuk ke dalam daftar pemain termuda karena ia sudah bermain di piala dunia saat umurnya tahun hari pada saat itu eto o harus menjalani laga melawan italia pada fase grup piala dunia yang digelar di perancis femi opabunmi adalah pesepak bola dari benua afrika yang masuk ke dalam daftar ini selain eto o 
eks penyerang timnas nigeria itu melakukan debutnya di piala dunia di korea selatan jepang saat laga melawan inggris pada babak grup f pada saat itu femi opabunmi melakukan debutnya 
di usia tahun hari baca juga sosok juara piala dunia sebagai pemain dan pelatih masih dari benua afrika kini ada salomon olembe yang pernah membela kamerun di piala dunia saat umurnya masih tahun hari kala itu ia bermain untuk kamerun di piala dunia dan dimainkan saat bertemu dengan austria pele melakukan debutnya di ajang piala dunia saat berumur tahun dan hari baca juga hari jelang piala dunia raih piala dunia janji pele kecil untuk ayahnya jadi kenyataan eks pemain new york cosmos itu melakukan debutnya saat laga brasil melawan uni soviet pada piala dunia pada penampilan perdananya di pentas piala dunia pele berhasil membawa brasil menjadi kampiun untuk pertama kalinya usai menundukkan perlawanan tuan rumah swedia dengan skor

----------------------------------------------------------------------------------------------------
query: shin tae yong
the document with highest cosine probability:
similar documents: 0.49747838034752195
 kompas com juru racik timnas u indonesia shin tae yong menyampaikan ucapan terima kasih kepada luna maya ini bermula dari story instagram luna maya yang memberikan suntikan semangat buat shin tae yong guna menghadapi kualifikasi piala asia u dalam unggahan itu luna maya memajang foto bersama shin tae yong keduanya berpose dengan membentuk tanda cinta di jari mereka semoga beruntung untuk pertandingan selanjutnya ayo indonesia tulis luna maya dengan menandai akun instagram shin tae yong baca juga jadwal timnas u indonesia di kualifikasi piala asia u vietnam lawan terakhir shin tae yong menyambut positif dukungan yang diberikan oleh luna maya di media sosial instagram pelatih asal korea selatan itu mengucapkan terima kasih atas support luna maya buat timnas indonesia menurut shin tae yong dukungan dari luna maya bisa membuat pemain timnas indonesia senang terima kasih luna atas dukungan luna terhadap timnas tulis shin tae yong di instagram story nya baca juga shin tae yong datang persija lepas pemain ke timnas u indonesia para pemain timnas indonesia pasti akan senang tambah pelatih yang membawa timnas indonesia ke final piala aff adapun timnas u indonesia besutan shin tae yong bakal tampil dalam kualifikasi piala asia u timnas u indonesia tergabung dalam grup f kualifikasi piala asia berrsama hong kong timor leste dan vietnam seluruh pertandingan grup f kualifikasi piala asia bakal berpusat di stadion gelora bung tomo surabaya jawa 
timur september rintangan pertama timnas indonesia di kualifikasi piala asia u ketika melawan timor leste baca juga shin tae yong berpesan untuk timnas u bola datang jangan menunggu 
laga timnas u indonesia vs timor leste dalam jadwal kualifikasi piala asia u akan digelar di stadion gelora bung tomo pada rabu timnas indonesia wajib untuk menang sebab hasil positif dapat menambah kepercayaan diri sebelum melawan hong kong september dan vietnam september jika ingin lolos ke piala asia u timnas indonesia harus keluar sebagai juara grup atau setidaknya runner up terbaik mochamad hary prasetya


