- server.py ve client.py yaz�l�mlar� linux ortam�nda �al��maktad�r.
- server.py dosyas� �al��t�rmak i�in 'sudo python3 server.py' komutu girilmelidir.
- client.py dosyas� �al��t�rmak i�in 'python3 client.py' komutu girilmelidir.

SUNUCU:
- sunucu 142. portu dinlemektedir.
- sunucu zaman� dilimini UTC-3 bi�iminde, milisaniye cinsinden d�nd�rmektedir.
- server.py dosyas�n�n 7. sat�r�nda bulunan utc_time de�i�keni ile istemcinin d�nd�rece�i UTC zaman dilimi ayarlanabilir.

�STEMC�:
- istemci hedef portu 142'dir.
- client.py dosyas� �al��t�r�ld���nda sunucu ip adresi girilmelidir.
- istemci ntp senkronizasyonunu kapatarak sunucudan ald��� yan�ta g�re zaman dilimini ayarlar.