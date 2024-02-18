# Học Windows Forms App (.NET Framework)
1. để in thông báo: MessageBox.Show("Welcome to C#");
2. căn chỉnh văn bản: TextAlign: Center.
3. làm cho cái TextBox chỉ đọc: ReadOnly: true.
# Toolbox (Chứa các control)
1. Panel - bảng điều khiển.
2. Label - nhãn mác.
3. TextBox - hộp văn bản.
4. Button - cái nút.
5. MenuStrip - dải menu.
6. ListView - chế độ xem danh sách.
7. ComboBox - hộp tổ hợp.
8. NumericUpDown - số lên xuống.
9. FlowLayoutPanel - bảng điều khiển bố cục luồng.
# Vị trí của chương trình lúc chạy
Sử dụng StartPosition: CenterScreen (nó sẽ ra chính giữa màn hình)
# Ẩn mật khẩu cho TextBox
Sử dụng UseSystemPasswordChar: true
# Thiết lập TabIndex
Lập trình Win Form thì nhớ phải thiết lập TabIndex cho TextBox, Button<br>
Ví dụ:<br>
<code>this.txbUserName.TabIndex = 1;
this.txbPassword.TabIndex = 2;
this.btnLogin.TabIndex = 3;
this.btnExit.TabIndex = 4;
</code>
# Thêm một form mới
Bước 1: bấm chuột phải vào Project (không bấm chuột phải vào Solution nha).<br>
Bước 2: Chọn Add.<br>
Bước 3: Chọn New Item.<br>
Bước 4: Chọn Form (Windows Forms), nó sẽ gợi ý là Form1.cs đấy.<br>
Bước 5: Đặt tên Form theo ý thích rồi bấm Add.
# Tác dụng của FlowLayoutPanel
danh sách không cố định, nhiều khi là N phần tử thì sao<br>
rồi mỗi lần thêm thì nó sẽ tự động xếp đầy panel, không đi ra ngoài<br>
đỡ được công việc thiết lập vị trí cho các phần tử (set position)
# Khi bạn bấm Enter trên Win Form
khi bạn bấm Enter trên Win Form<br>
thì bạn muốn nó tự động ăn vào button đăng nhập<br>
vậy bạn cần thiết lập thuộc tính AcceptButton của đối tượng Form<br>
ví dụ: AcceptButton: btnLogin
