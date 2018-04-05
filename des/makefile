all: DES_ECB_Enc DES_ECB_Dec

DES_ECB_Enc: DES_ECB_Enc.c
	gcc -o DES_ECB_Enc DES_ECB_Enc.c -lssl -lcrypto -w

DES_ECB_Dec: DES_ECB_Dec.c
	gcc -o DES_ECB_Dec DES_ECB_Dec.c -lssl -lcrypto -w

clean:
	rm -f DES_ECB_Enc DES_ECB_Dec ciphersize.txt CS468-HW2-mydesecb.txt CS468-HW2.mydesecb
