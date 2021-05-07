membuat kalkulator sederhana

![membuat kalkulator sederhana](https://user-images.githubusercontent.com/56861575/117395180-ad3a6900-af21-11eb-829e-3491671523a3.jpeg)
![membuat kalkulator sederhana (2)](https://user-images.githubusercontent.com/56861575/117468415-d9d09e00-af7e-11eb-9be5-35bec0eb50a2.jpeg)
![membuat kalkulator sederhana (3)](https://user-images.githubusercontent.com/56861575/117468454-e5bc6000-af7e-11eb-9547-4f4803dd8a59.jpeg)


Hasil

![membuat kalkulator sederhana(1)](https://user-images.githubusercontent.com/56861575/117395335-ed015080-af21-11eb-8215-e16885159080.jpeg)

sintak  :

angka_pertama  = str2double (get (handles.edit1,’string’));
angka_kedua = str2double(get(handles.edit2,’string’));
operator = get (handels.popupmenu1, ‘value’);
if operator == 1
	hasil/= angka_pertama + angka_kedua;
elseif operator == 2
	hasil = angka_pertama – angka_kedua;
elseif operator == 3
	hasil = angka_pertama * angka_kedua;
elseif operator == 4
	hasil = angka_pertama / angka_kedua;
end
set(handels.edit3; ‘string’,num2str (hasil1));

