# BCPHP1-doc-so

[Bài tập] Ứng dụng đọc số thành chữ
Mục tiêu
Bài tập này củng cố kỹ năng sử dụng cấu trúc rẽ nhánh.

Mô tả
Giả sử bạn đang tham gia viết chương trình cho máy đo chiều cao cân nặng, hãy viết một chương trình có khả năng đọc các số nguyên không âm có tối đa 3 chữ số.

Ví dụ, với số 261, chương trình in ra màn hình two hundred and sixty one.

Hướng dẫn
Bước 1: viết mã để chương trình hỏi số cần đọc

Bước 2: đọc các số có một chữ số

Nếu số cần đọc nhỏ hơn 10 và lớn hơn hoặc bằng 0, hãy sử dụng cấu trúc switch case để đọc số đó.

Nếu số cần đọc vượt quá khả năng, in ra chuỗi out of ability

Bước 3: đọc các số có hai chữ số nhỏ hơn 20

Trong trường hợp số cần đọc nhỏ hơn 20 và lớn hơn hoặc bằng 10, tính ra số hàng đơn vị (ones), sau đó sử dụng cấu trúc switch case để đọc số thành các string tương ứng.

Ví dụ: từ số 16, có số 6, đọc thành sixteen.
Bước 4: đọc các số có hai chữ số lớn hơn hoặc bằng 20

Trong trường hợp số cần đọc nhỏ hơn 100 và lớn hơn hoặc bằng 20, tính ra số hàng chục và số hàng đơn vị (ones).

Ví dụ, từ 61 có tens = 6 và ones = 1.

Sử dụng cấu trúc switch case để đọc riêng biệt hàng chục và hàng đơn vị thành chữ, ghép lại thành câu hoàn chỉnh.

Ví dụ, từ 61 có sixty và one, ghép lại thành sixty one.

Bước 5: đọc các số có ba chữ số

Đọc chữ số hàng trăm thành chữ, sử dụng thuật toán đã có để đọc phần còn lại của số thành chữ và ghép lại để được số hoàn chỉnh.

Ví dụ từ 461 có four hundred và sixty one, ghép lại thành four hundred and sixty one.
