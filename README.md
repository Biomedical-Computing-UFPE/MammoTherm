# MammoTherm
Thermographic mammary images database for breast cancer research

* In order to use this database, please cite the following references:

Bezerra, L. A., Ribeiro, R. R., Lyra, P. R. M., & Lima, R. C. F. (2020). An empirical correlation to estimate thermal properties of the 
breast and of the breast nodule using thermographic images and optimization techniques. International Journal of Heat and Mass Transfer, 
149, 119215.

Rodrigues, A. L., de Santana, M. A., Azevedo, W. W., Bezerra, R. S., Barbosa, V. A., de Lima, R. C., & dos Santos, W. P. (2019). 
Identification of mammary lesions in thermographic images: feature selection study using genetic algorithms and particle swarm 
optimization. Research on Biomedical Engineering, 35(3), 213-222.

Santana, M. A. D., Pereira, J. M. S., Silva, F. L. D., Lima, N. M. D., Sousa, F. N. D., Arruda, G. M. S. D., ... & Santos, W. P. D. 
(2018). Breast cancer diagnosis based on mammary thermography and extreme learning machines. Research on Biomedical Engineering, 34(1), 
45-53.

de Vasconcelos, J. H., dos Santos, W. P., & de Lima, R. C. F. (2018). Analysis of methods of classification of breast thermographic 
images to determine their viability in the early breast cancer detection. IEEE Latin America Transactions, 16(6), 1631-1637.

Araújo, M. C., Souza, R. M., Lima, R. C., & Silva Filho, T. M. (2017). An interval prototype classifier based on a parameterized 
distance applied to breast thermographic images. Medical & Biological Engineering & Computing, 55(6), 873-884.

----------------------------------------------------------------------------------------------------------------------------------------

Database Information - Mammary Thermography

Cyst: 219 images
LEMD: 25 
LEME: 33 
LIMD: 11 
LIME: 17 
MD: 27 
ME: 33 
T1: 31 
T2: 42 

Benign Lesion: 371 images
LEMD: 44
	LEME: 47
	LIMD: 34
	LIME: 30
	MD: 48
	ME: 47
	T1: 49
	T2: 72

Malignant Lesion: 235 images
	LEMD: 23
	LEME: 21
	LIMD: 24
	LIME: 22
	MD: 36
	ME: 33
	T1: 33
	T2: 43

No-Lesion: 227 images
	LEMD: 36
	LEME: 33
	LIMD: 21
	LIME: 22
	MD: 25
	ME: 24
	T1: 23
	T2: 43

Inconclusive: 360 images
	LEMD: 37
	LEME: 42
	LIMD: 22
	LIME: 23
	MD: 51
	ME: 60
	T1: 50
	T2: 75

Without diagnosis: 2469 images
	LEMD: 339
	LEME: 327
	LIMD: 244
	LIME: 211
	MD: 299
	ME: 295
	T1: 283
	T2: 471

Total of images: 3881
Total of "useful" images: 1052
	('useful' -> neither "inconclusive" nor "without diagnosis")


Legend:
	LEMD - external lateral of the right breast
	LEME - external lateral of the left breast
	LIMD - internal lateral of the right breast
	LIME - internal lateral of the left breast
	MD - right breast (frontal)
	ME - left breast (frontal)
	T1 - frontal with arms down (bilateral)
	T2 - frontal with arms up (bilateral)

