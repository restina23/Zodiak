# Zodiak

12 Urutan Zodiak Menurut Astrologi

Capricorn (21 Desember – 19 Januari)
Aquarius (20 Januari – 18 Februari)
Pisces (19 Februari – 20 Maret)
Aries (21 Maret – 20 April)
Taurus (21 April – 20 Mei)
Gemini (21 Mei – 20 Juni)
Cancer (21 Juni – 20 Juli)
Leo (21 Juli – 21 Agustus)
Virgo (22 Agustus – 22 September)
Libra (23 September – 22 Oktober)
Scorpio (23 Oktober – 22 November)
Sagitarius (23 November – 20 Desember)


#What is your zodiac sign?

nama= input("Siapa Nama Kamu : ")

day = int(input("Masukkan Tanggal Lahir: 1,2,3,dst.): "))

month = input("Masukkan Bulan Lahir(contoh: januari, februari, maret,april,dst.): ")

if month == 'januari':

	zodiac = 'Capricorn' if (day <= 19) else 'aquarius'

elif month == 'februari':

	zodiac = 'Aquarius' if (day <= 18) else 'pisces'

elif month == 'maret':

	zodiac = 'Pisces' if (day <= 20) else 'aries'

elif month == 'april':

	zodiac = 'Aries' if (day <= 20) else 'taurus'

elif month == 'mei':

	zodiac = 'Taurus' if (day <= 20) else 'gemini'

elif month == 'juni':

	zodiac = 'Gemini' if (day <= 20) else 'cancer'

elif month == 'juli':

	zodiac = 'Cancer' if (day <= 20) else 'leo'

elif month == 'agustus':

	zodiac = 'Leo' if (day <= 21) else 'virgo'
	
	
elif month == 'september':

	zodiac = 'Virgo' if (day <= 22) else 'libra'

elif month == 'oktober':

	zodiac = 'Libra' if (day <= 22) else 'scorpio'

elif month == 'november':

	zodiac = 'scorpio' if (day <= 22) else 'sagittarius'
	
elif month == 'desember':

	zodiac = 'Sagittarius' if (day <= 20) else 'capricorn'

print("Hallo", nama, "zodiak kamu adalah", zodiac)
