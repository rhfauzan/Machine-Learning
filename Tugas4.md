1.	Naive Bayes Classification
   
  1.1.	Pengenalan Bayes Theorem | Teori Bayes | Conditional Probability
  -	Bayes' theorem menawarkan suatu formula untuk menghitung nilai probability dari suatu event dengan memanfaatkan pengetahuan sebelumnya dari kondisi terkait; atau sering kali dikenal dengan istilah conditional probability.
  ![image](https://github.com/user-attachments/assets/e379d68d-6e68-42f5-820e-2ac56cad6ee0)

  1.2.	Pengenalan Naive Bayes Classification
  -	Pengklasifikasi naif Bayes adalah keluarga "pengklasifikasi probabilistik" linier yang mengasumsikan bahwa fitur-fiturnya independen secara kondisional, mengingat kelas targetnya.

  1.3.	Pengenalan Prior Probability
  -	Distribusi probabilitas sebelumnya dari kuantitas yang tidak pasti, sering kali disebut prior, adalah distribusi probabilitas yang diasumsikan sebelum beberapa bukti diperhitungkan. Misalnya, prior dapat berupa distribusi probabilitas yang mewakili proporsi relatif pemilih yang akan memilih politisi tertentu pada pemilu mendatang. Kuantitas yang tidak diketahui mungkin merupakan parameter model atau variabel laten, bukan variabel yang dapat diamati.

  1.4.	Pengenalan Likelihood
  -	mengukur seberapa baik model statistik menjelaskan data yang diamati dengan menghitung probabilitas melihat data tersebut berdasarkan nilai parameter model yang berbeda. Hal ini dibangun dari distribusi probabilitas gabungan dari variabel acak yang (mungkin) menghasilkan observasi.
  ![image](https://github.com/user-attachments/assets/ad178dda-381c-4c88-aea2-631161b129d6)
  Lakukan prediksi siapa pelanggan yang melakukan pemesanan dengan diketahui pesanannya adalah lumpia dan bakso.

P(Asep)=0.5

P(Joko)=0.5

Asep:
■(P(lumpia,bakso|Asep)&=(0.1×0.8)@&=0.08)

Joko:
■(P(lumpia,bakso|Joko)&=(0.3×0.2)@&=0.06)
		Evidence atau Normalizer: P(X)
  
■(Evidence&=∑(Likelihood×Prior)@P(lumpia,bakso)&=(0.08×0.5)+(0.06×0.5)@&=0.07)

1.5.	Pengenalan Evidence | Normalizer
![image](https://github.com/user-attachments/assets/99149899-cfd1-4443-9ad9-89bd4be4cb55)
Lakukan prediksi siapa pelanggan yang melakukan pemesanan dengan diketahui pesanannya adalah siomay dan bakso.

Posterior Probability: P(y|X)

pesanan: siomay, bakso

Evidence: P(X)

■(P(siomay,bakso)&=(0.1×0.8×0.5)+(0.5×0.2×0.5)@&=0.09)
	
 Asep:
■(P(Asep|siomay,bakso)&=((0.1×0.8)×0.5)/0.09@&=0.444)
	
 Joko:
■(P(Joko|siomay,bakso)&=((0.5×0.2)×0.5)/0.09@&=0.555)

Pengenalan Posterior Probability

Probabilitas posterior adalah jenis probabilitas bersyarat yang dihasilkan dari pemutakhiran probabilitas sebelumnya dengan informasi yang dirangkum oleh kemungkinan melalui penerapan aturan Bayes.
 
  Formula:
Posterior=(Likelihood×Prior)/Evidence

 Asep:
■(P(Asep|lumpia,bakso)&=(0.08×0.5)/0.07@&=0.57)

 Joko:
■(P(Joko|lumpia,bakso)&=(0.06×0.5)/0.07@&=0.43)
 
1.7.	Studi kasus dan implementasi Naive Baye
![image](https://github.com/user-attachments/assets/4f2746d2-e3a2-4d71-bc04-4b21ac8462cd)

![image](https://github.com/user-attachments/assets/1818ecd7-1cf9-4468-b333-ada84d437eef)

![image](https://github.com/user-attachments/assets/7fa480d1-8196-4f6b-b601-d517453f2609)

![image](https://github.com/user-attachments/assets/9daddcc7-2c19-41f7-923c-4a809012ef15)
