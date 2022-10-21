# sinav-hesaplama
name = input('Öğrenci İsmi: ')
surname = input('Öğrenci Soyadı: ')
no = int(input('Öğrenci Okul Numarası: '))
lesson = input('Ders Adı: ')
Midterm_exam = float(input('Vize Notu: '))
final_exam = float(input('Final Notu: '))

average = ((Midterm_exam * 0.40) + (final_exam * 0.60))

if (average >= 0) and (average < 45):
    print(f'Öğrenci Ortalaması: {average}, Harf Notunuz: FF')
elif (average>= 45) and (average < 58):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: DD')
elif (average >= 58) and (average < 65):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: DE')
elif (average >= 65) and (average < 72):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: CD')
elif (average >= 72) and (average < 75):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: CC')
elif (average >= 75) and (average < 81):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: BC')
elif (average>= 81) and (average < 86):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: BB')
elif (average >= 86) and (average< 92):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: BA')
elif (average>= 92) and (average < 101):
    print(f'Öğrenci Ortalaması: {average}, Harf Notu: AA')
else:
    print('Yanlış bilgi girdiniz. Lütfen girmiş olduğunuz öğrenci bilgilerini kontrol ediniz.')
