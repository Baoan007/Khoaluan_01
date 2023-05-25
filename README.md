
=============Các câu lệnh=============
# cho phép các nguồn tài nguyên như html, css, javascript... được truy vấn cùng lúc với các domain khác nhau:
# mở Server thứ 1 để chạy lệnh sau:
rasa run -m models --enable-api --cors "*" --debug

# rasa run actions
# mở Server thứ 2 để chạy lệnh sau:
rasa run actions
