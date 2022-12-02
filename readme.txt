öğrenci not sistemi

sınıflar;

Course;
nitelikler: name, code, prefix(örn tarih dersine
sadece tarih dersinin eklenebilmesi için gerekli, note, Teacher
metotlar: course(), addTeacher(), printTeacher()

Teacher;
nitelikler: name, phone, branch
metotlar; teacher()

Student;
nitelikler; name, stuNo, classes, course1, course2, course3, avarage, isPass
metotlar; Student(), addBulkExamNote(), isPass(), calcAvarage(), printNote()

ödev:
sözlü notu kısmı eklenecek
ortalamaya etkisini her ders için ayrı ayrı belirt.
sözlü notunun o dersin ortalamasına etkisi 0.2, sınavın etkis 0.8

