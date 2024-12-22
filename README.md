# vimtutor
# Di chuyển con trỏ và chế độ Normal
- Sử dụng các phím: h (trái), j (xuống), k (lên), l (phải).
- Các chế độ trong Vim:
  + Normal mode: Chế độ mặc định để di chuyển, chỉnh sửa.
  + Insert mode: Nhấn i để nhập văn bản.
  + Trở lại Normal mode: Nhấn Esc.

# Chỉnh sửa văn bản
- Xóa ký tự: Nhấn x để xóa ký tự dưới con trỏ.
- Undo và Redo:
  + Undo: u.
  + Redo: Ctrl + r.

# Chèn và thay thế văn bản
- Chèn văn bản:
  + i: Chèn trước con trỏ.
  + a: Chèn sau con trỏ.
  + o: Mở dòng mới bên dưới.
- Thay thế ký tự: r (thay thế ký tự dưới con trỏ).

#  Lưu và thoát 
- Lưu tệp:
  + :w (write).
- Thoát:
  + :q (quit).
- Lưu và thoát:
  + :wq hoặc ZZ.
- Thoát mà không lưu:
  + :q!.

 # Xóa, sao chép và dán
- xóa:
  + dd: Xóa cả dòng.
- Sao chép (yank):
  + yy: Sao chép dòng hiện tại.
- Dán:
  + p: Dán sau con trỏ.
  + P: Dán trước con trỏ.
#  Tìm kiếm và thay thế
- Tìm kiếm:
  + /từ_khóa: Tìm từ khóa xuống dưới.
  + ?từ_khóa: Tìm từ khóa lên trên.
  + n: Tìm tiếp.
  + N: Tìm ngược.
- Thay thế:
  + :s/cũ/mới/: Thay thế từ đầu tiên trên dòng hiện tại.
  + :s/cũ/mới/g: Thay tất cả trên dòng.
  + :%s/cũ/mới/g: Thay tất cả trong tệp.
# Chuyển đến vị trí cụ thể
- G: Đến cuối tệp.
- gg: Đến đầu tệp.
- :số_dòng: Đến dòng cụ thể.
- { và }: Di chuyển giữa các đoạn.

# Làm việc với nhiều tệp
- Mở tệp khác:
  + :e tên_tệp.
- Chuyển đổi giữa các tệp:
  + :n (Next).
  + :prev (Previous).

# Các lệnh nâng cao
- Lựa chọn khối văn bản:
  + v: Chế độ visual.
  + V: Chế độ visual theo dòng.
  + Ctrl + v: Chế độ visual block.
- Indent:
  + >>: Thụt vào.
  + <<: Thụt ra.
