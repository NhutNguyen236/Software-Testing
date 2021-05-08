# Project note

<details>
<summary>Requirement</summary>

- Mỗi bạn trong nhóm viết 3 Test cases cho 3 tính năng khác nhau trên app đó.
**Lưu ý: Các Test cases ko được trùng với các bạn khác.**

- Test cases của bạn nào thì bạn đó sẽ dùng TestArchitect để tự động hóa những Test case đó.

- Nhóm tạo 1 repo chung, đặt tên repo: NhomID_AUT (ví dụ: Nhom01_App01)

- Nhóm tạo số lượng repo users tương ứng với số người trong nhóm, username đặt theo quy tắc: tên.họ (ví dụ: Nhóm có 2 người => tạo 2 repo users: ten1.ho1; ten2.ho2). Mỗi người tự đổi password cho user tương ứng của mình.

- Dùng user tên họ của mình khi làm bài tập nhóm. KO dùng user 'administrator' khi làm bài tập nhóm.
</details>

<details>
<summary>Evaluation</summary>
Tiêu chí đánh giá: Khi thỏa tất cả các tiêu chí phía dưới đây sẽ được 10đ.

1. Đặt tên theo quy tắc

2. Scripts được tổ chức tốt (Test module, TC, Actions, Interface) -> lên kế hoạch, có big picture trước khi thực hiện.

3. Tất cả TCs được viết theo phương pháp ABT (thông qua phân tích TMs, TCs, High-level actions) -> 1đ. Ko thỏa thì trừ 1đ.

4. Interface:

    - Rõ ràng, sạch đẹp, đặt tên dễ hiểu và hình dung.

    - Control ko được bắt trùng.

5. Test Module, Test cases:

    - Phải run được.

    - Phải run đúng như được viết ra. Ko bị thiếu step, hay dư step. Ko bị thiếu VP hay dư VP.

    - Biến phải được đặt tên và khai báo tốt (ko có biến trùng, ko có biến khai báo nhưng ko xài).

    - Luôn có Initial (chuẩn bị test data, có hoặc ko precondition cho Test Module) và Final (dọn môi trường - trả lại trạng thái trước khi run, xóa data được tạo trong quá trình chạy test, v..v..).

    - Phải có test objectives. Test case phải có test steps đầy đủ.

6. High-level actions:

    - Biến được đặt tên và khai báo tốt (ko có biến trùng, ko đc có biến khai báo nhưng ko xài).

    - Phần phụ thêm, ko bắt buộc: Nếu có phân biệt tốt loại biến khi sử dụng (local hay global) cộng 0.5đ.

    - Action phải được viết theo cách có thể tái sử dụng, dễ sử dụng theo người dùng (ko phải theo người viết). Tránh dup code (đoạn code lặp lại chỗ khác), hay viết nhưng ko dùng / ko có ý nghĩa.

    - Bên trong Action nếu có comment đầy đủ, đánh dấu từng bước/khâu xử lý bên trong để người khác dễ dàng đọc hiểu. Thì được cộng 0.5đ.

<details>