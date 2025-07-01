# i2intern-hazelcast2
Bu proje, i2i Systems staj programı kapsamında gerçekleştirildi. Bu ödevde, Hazelcast ve Hazelcast Management Center konteynerleri Docker kullanılarak yerel makinede çalıştırıldı. Docker kullanarak, Hazelcast kümesi ve yönetim paneli başlatma öğrenildi.

# Hazelcast Konteynerini Çekmek ve Çalıştırmak:

docker pull hazelcast/hazelcast:latest 
Bu komut,Hazelcast'ın en son sürümünü Docker Hub'dan indirir.

docker run hazelcast/hazelcast:latest
Bu komut,indirilen Hazelcast sürümünü çalıştırır.

#Hazelcast Management Center Konteynerini Çekmek ve Çalıştırmak:

docker pull hazelcast/management-center:latest
Bu komut, Hazelcast Management Center'ın en son sürümünü Docker Hub'dan indirir.

docker run --rm -p 8080:8080 hazelcast/management-center:latest
Bu komut, Hazelcast Management Center'ı başlatır ve 8080 portu üzerinden erişilebilir hale getirir.
