Programa testuoja ir palygina std::vector ir std::list naudodama įvairaus dydžio sąrašus ir tris skirtingas strategijas.

Naudota įranga:

CPU: AMD Ryzen 5 2600 Six-Core Processor, 3400 MHz, 6 Cores, 12 Logical Processors.

RAM: 16GB

SSD

Pirmoji strategija:

![pirmoji_strategija](https://user-images.githubusercontent.com/113544863/202709590-d9ab50fd-dcf6-4694-ab34-15015c81b987.PNG)


Šioje strategijoje spartos padidinimui buvo panaudotos remove_if ir remove_copy_if funkcijos.
Antra strategija be šių funkcijų:

![antroji_strategija](https://user-images.githubusercontent.com/113544863/202709614-a412011d-c38d-4195-9c29-d55db6ef75c1.PNG)

Antra strategija su šiomis funkcijomis:

![Capture](https://user-images.githubusercontent.com/113544863/202712500-2746a973-d990-4949-94fd-109275697014.PNG)


Trečioji strategija:

![trecioji_strategija](https://user-images.githubusercontent.com/113544863/202709627-baab2382-c175-48d4-b405-3ac8eced79af.PNG)
