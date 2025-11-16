Yêu cầu:

- Theo hướng dẫn trong file CS251-proj2-bitcoin-transactions.pdf, thực hiện các Exercise 1, 2, 3 (không làm Exercise 4).
- Sửa và chạy source code trong các file Q1.py, Q2a.py, Q2b.py, Q3a.py, Q3b.py. Ghi kết quả lại trong file docs/transactions.py theo hướng dẫn ở trên.

Lưu ý:
- Có 2 loại address là legacy (cũ, bắt đầu với m…/n…) và segwit (mới, bắt đầu với tb1q…). Một số faucet chỉ chấp nhận segwit address. Tuy nhiên, lab 2 starter code được chuẩn bị cho legacy address. Nếu bạn dùng segwit address thì cần fix 1 số lỗi. Nên dùng legacy address để làm bài lab. Dùng segwit address là thực hành nâng cao, không bắt buộc.
- Trong file lib/config.py có yêu cầu secret_key_BCY cho Exercise 4. Chúng ta không làm Exercise 4 và không cần tạo địa chỉ BCY. Tuy nhiên cần comment out các phần code liên quan để tránh bị lỗi khi import và gọi hàm.

Nộp: file zip, bao gồm
- source code đã hoàn thiện
- docs/transactions.py
